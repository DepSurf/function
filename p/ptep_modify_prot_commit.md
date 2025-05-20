# Function: <code>ptep_modify_prot_commit</code>

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
In mm/mprotect.c (ffffffff811c890d)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff81278f45)
Location: arch/x86/include/asm/paravirt.h:472
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
In mm/mprotect.c (ffffffff811e4bcb)
Location: arch/x86/include/asm/paravirt.h:445
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812a59e5)
Location: arch/x86/include/asm/paravirt.h:445
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
In mm/memory.c (ffffffff811eaec4)
Location: arch/x86/include/asm/paravirt.h:436
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811f4bf4)
Location: arch/x86/include/asm/paravirt.h:436
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812bb32d)
Location: arch/x86/include/asm/paravirt.h:436
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
In mm/memory.c (ffffffff811f5fd8)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811ffaaf)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812c694d)
Location: arch/x86/include/asm/paravirt.h:444
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
In mm/memory.c (ffffffff8120dc36)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812181e7)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff812ece95)
Location: arch/x86/include/asm/paravirt.h:430
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
In mm/memory.c (ffffffff8122e6cc)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff8123931b)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813192ed)
Location: arch/x86/include/asm/paravirt.h:430
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
In mm/memory.c (ffffffff812425e3)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8124d8be)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff81330905)
Location: arch/x86/include/asm/paravirt.h:435
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
In mm/memory.c (ffffffff812513af)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8125f8bc)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8135872c)
Location: arch/x86/include/asm/paravirt.h:435
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
In mm/memory.c (ffffffff8125f95f)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126e0cc)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8137097c)
Location: arch/x86/include/asm/paravirt.h:423
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
In mm/memory.c (ffffffff8128fe13)
Location: arch/x86/include/asm/paravirt.h:437
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8129e6f1)
Location: arch/x86/include/asm/paravirt.h:437
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c6fc)
Location: arch/x86/include/asm/paravirt.h:437
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff813b8fac)
Location: arch/x86/include/asm/paravirt.h:437
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
In mm/memory.c (ffffffff8129a897)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812a9ab1)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131863c)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff813c7f7e)
Location: arch/x86/include/asm/paravirt.h:403
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
In mm/memory.c (ffffffff8129fd8c)
Location: arch/x86/include/asm/paravirt.h:426
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812aef3c)
Location: arch/x86/include/asm/paravirt.h:426
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e82c)
Location: arch/x86/include/asm/paravirt.h:426
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff813cefae)
Location: arch/x86/include/asm/paravirt.h:426
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
In mm/memory.c (ffffffff812e3378)
Location: arch/x86/include/asm/paravirt.h:426
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812f072c)
Location: arch/x86/include/asm/paravirt.h:426
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bc0c)
Location: arch/x86/include/asm/paravirt.h:426
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8142048e)
Location: arch/x86/include/asm/paravirt.h:426
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
In mm/memory.c (ffffffff813446d6)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81353d3f)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9dd3)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8149a896)
Location: arch/x86/include/asm/paravirt.h:432
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
In mm/memory.c (ffffffff813bc830)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff813ce1f4)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471e50)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8152edb6)
Location: arch/x86/include/asm/paravirt.h:432
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
In mm/memory.c (ffffffff813f121b)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81402aa8)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6793)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff815670c6)
Location: arch/x86/include/asm/paravirt.h:427
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
In mm/memory.c (ffffffff8141c134)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8142f100)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7811)
Location: arch/x86/include/asm/paravirt.h:427
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159cdfc)
Location: arch/x86/include/asm/paravirt.h:427
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
In mm/memory.c (ffff8000102fa0c8)
Location: include/asm-generic/pgtable.h:658
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffff8000103052d8)
Location: include/asm-generic/pgtable.h:658
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
Location: include/asm-generic/pgtable.h:658
Inline: True
```
```
In mm/mprotect.c (c05233b8)
Location: include/asm-generic/pgtable.h:658
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
void ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t old_pte, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c0000000000914a0)
Location: arch/powerpc/mm/book3s64/pgtable.c:436
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
c0000000000914a0-c000000000091500: ptep_modify_prot_commit (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:658
Inline: True
```
```
In mm/mprotect.c (ffffffe00021122c)
Location: include/asm-generic/pgtable.h:658
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
In mm/memory.c (ffffffff81257faf)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126671c)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81368f5c)
Location: arch/x86/include/asm/paravirt.h:423
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
In mm/memory.c (ffffffff8124da9a)
Location: include/asm-generic/pgtable.h:658
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81258de6)
Location: include/asm-generic/pgtable.h:658
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff8135a1eb)
Location: include/asm-generic/pgtable.h:658
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
In mm/memory.c (ffffffff81255d4f)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812644bc)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81366a2c)
Location: arch/x86/include/asm/paravirt.h:423
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
In mm/memory.c (ffffffff812657df)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81273e7c)
Location: arch/x86/include/asm/paravirt.h:423
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8137a088)
Location: arch/x86/include/asm/paravirt.h:423
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
