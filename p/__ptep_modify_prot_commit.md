# Function: <code>__ptep_modify_prot_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101df00)
Location: include/asm-generic/pgtable.h:405
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff810646d0)
Location: include/asm-generic/pgtable.h:405
Inline: False
```
**Symbols:**

```
ffffffff8101df00-ffffffff8101df0d: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff810646d0-ffffffff810646dd: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d2f0)
Location: include/asm-generic/pgtable.h:410
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064320)
Location: include/asm-generic/pgtable.h:410
Inline: False
```
**Symbols:**

```
ffffffff8101d2f0-ffffffff8101d2fd: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81064320-ffffffff8106432d: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101da10)
Location: include/asm-generic/pgtable.h:434
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677f0)
Location: include/asm-generic/pgtable.h:434
Inline: False
```
**Symbols:**

```
ffffffff8101da10-ffffffff8101da1d: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff810677f0-ffffffff810677fd: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8101fcf0)
Location: include/asm-generic/pgtable.h:539
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066ac0)
Location: include/asm-generic/pgtable.h:539
Inline: False
```
**Symbols:**

```
ffffffff8101fcf0-ffffffff8101fcfd: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81066ac0-ffffffff81066acd: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020950)
Location: include/asm-generic/pgtable.h:540
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ac40)
Location: include/asm-generic/pgtable.h:540
Inline: False
```
**Symbols:**

```
ffffffff81020950-ffffffff8102095d: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff8106ac40-ffffffff8106ac4d: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021400)
Location: include/asm-generic/pgtable.h:583
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106d900)
Location: include/asm-generic/pgtable.h:583
Inline: False
```
**Symbols:**

```
ffffffff81021400-ffffffff8102140d: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff8106d900-ffffffff8106d90d: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020c70)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073aa0)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
**Symbols:**

```
ffffffff81020c70-ffffffff81020c7d: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81073aa0-ffffffff81073aad: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810227b0)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077600)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
**Symbols:**

```
ffffffff810227b0-ffffffff810227c1: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81077600-ffffffff81077611: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810230f0)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078670)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
**Symbols:**

```
ffffffff810230f0-ffffffff81023101: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81078670-ffffffff81078681: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025960)
Location: include/linux/pgtable.h:795
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fa70)
Location: include/linux/pgtable.h:795
Inline: False
```
**Symbols:**

```
ffffffff81025960-ffffffff81025971: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff8107fa70-ffffffff8107fa81: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026080)
Location: include/linux/pgtable.h:844
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f690)
Location: include/linux/pgtable.h:844
Inline: False
```
**Symbols:**

```
ffffffff81026080-ffffffff81026093: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff8107f690-ffffffff8107f6a3: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027fc0)
Location: include/linux/pgtable.h:844
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080790)
Location: include/linux/pgtable.h:844
Inline: False
```
**Symbols:**

```
ffffffff81027fc0-ffffffff81027fd3: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81080790-ffffffff810807a3: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f6b0)
Location: include/linux/pgtable.h:863
Inline: False
```
**Symbols:**

```
ffffffff8108f6b0-ffffffff8108f6c3: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0430)
Location: include/linux/pgtable.h:896
Inline: False
```
**Symbols:**

```
ffffffff810a0430-ffffffff810a045c: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b7fd0)
Location: include/linux/pgtable.h:932
Inline: False
```
**Symbols:**

```
ffffffff810b7fd0-ffffffff810b7ffc: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb180)
Location: include/linux/pgtable.h:944
Inline: False
```
**Symbols:**

```
ffffffff810bb180-ffffffff810bb1ac: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2d40)
Location: include/linux/pgtable.h:1075
Inline: False
```
**Symbols:**

```
ffffffff810c2d40-ffffffff810c2d84: __ptep_modify_prot_commit (STB_LOCAL)
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
Location: include/asm-generic/pgtable.h:621
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffff8000103052d8)
Location: include/asm-generic/pgtable.h:621
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
Location: include/asm-generic/pgtable.h:621
Inline: True
```
```
In mm/mprotect.c (c05233b8)
Location: include/asm-generic/pgtable.h:621
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
Location: include/asm-generic/pgtable.h:621
Inline: True
```
```
In mm/mprotect.c (ffffffe00021122c)
Location: include/asm-generic/pgtable.h:621
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
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023250)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077670)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
**Symbols:**

```
ffffffff81023250-ffffffff81023261: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81077670-ffffffff81077681: __ptep_modify_prot_commit (STB_LOCAL)
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
Location: include/asm-generic/pgtable.h:621
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81258de6)
Location: include/asm-generic/pgtable.h:621
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In fs/proc/task_mmu.c (ffffffff8135a1eb)
Location: include/asm-generic/pgtable.h:621
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810230b0)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077620)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
**Symbols:**

```
ffffffff810230b0-ffffffff810230c1: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff81077620-ffffffff81077631: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023520)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff810796c0)
Location: include/asm-generic/pgtable.h:621
Inline: False
```
**Symbols:**

```
ffffffff81023520-ffffffff81023531: __ptep_modify_prot_commit (STB_LOCAL)
ffffffff810796c0-ffffffff810796d1: __ptep_modify_prot_commit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
