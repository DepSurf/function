# Function: <code>ptep_modify_prot_start</code>

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
In mm/mprotect.c (ffffffff811c887c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff81278f34)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
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
In mm/mprotect.c (ffffffff811e4b3d)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812a59ce)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff811eae68)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811f4b66)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812bb316)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff811f5f81)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811ffa28)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812c6935)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8120dbd5)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff81218155)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812ece7d)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8122e638)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff8123926b)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813192dc)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8124253c)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8124d7f4)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff813308f4)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff812512f8)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8125f7fa)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8135871c)
Location: arch/x86/include/asm/paravirt.h:425
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8125f8a8)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126e00a)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8137096c)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8128fd58)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8129e611)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c6f5)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff813b8f9c)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8129a7d8)
Location: arch/x86/include/asm/paravirt.h:393
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812a99d1)
Location: arch/x86/include/asm/paravirt.h:393
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318635)
Location: arch/x86/include/asm/paravirt.h:393
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff813c7f6e)
Location: arch/x86/include/asm/paravirt.h:393
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffffffff8129fcc4)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812aee5c)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e825)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff813cef9e)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffffffff812e32b7)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812f064c)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bc05)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8142047e)
Location: arch/x86/include/asm/paravirt.h:416
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffffffff8134462a)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81353c5b)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9dcd)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8149a887)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffffffff813bc782)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff813ce13a)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471e4a)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8152eda7)
Location: arch/x86/include/asm/paravirt.h:422
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffffffff813f1170)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff814029ef)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a678d)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff815670b7)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffffffff8141c011)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8142eff5)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d780b)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159cdcb)
Location: arch/x86/include/asm/paravirt.h:417
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/memory.c (ffff8000102fa044)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffff80001030524c)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
Location: include/asm-generic/pgtable.h:647
Inline: True
```
```
In mm/mprotect.c (c0523374)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pte_t ptep_modify_prot_start(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000091360)
Location: arch/powerpc/mm/book3s64/pgtable.c:420
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
c000000000091360-c000000000091498: ptep_modify_prot_start (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:647
Inline: True
```
```
In mm/mprotect.c (ffffffe000211204)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/memory.c (ffffffff81257ef8)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126665a)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81368f4c)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff8124da0f)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81258d40)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff8135a1e0)
Location: include/asm-generic/pgtable.h:647
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81255c98)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812643fa)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81366a1c)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81265728)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81273dba)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8137a078)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
