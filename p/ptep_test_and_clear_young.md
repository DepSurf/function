# Function: <code>ptep_test_and_clear_young</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070fd0)
Location: arch/x86/mm/pgtable.c:447
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81070fd0-ffffffff81070ffb: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070f00)
Location: arch/x86/mm/pgtable.c:450
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81070f00-ffffffff81070f2a: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074a80)
Location: arch/x86/mm/pgtable.c:450
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81074a80-ffffffff81074aaa: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074010)
Location: arch/x86/mm/pgtable.c:480
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81074010-ffffffff8107403a: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079b25)
Location: arch/x86/mm/pgtable.c:480
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81079a40-ffffffff81079a71: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c6e5)
Location: arch/x86/mm/pgtable.c:485
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8107c610-ffffffff8107c640: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810830f5)
Location: arch/x86/mm/pgtable.c:551
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81083020-ffffffff81083050: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086d65)
Location: arch/x86/mm/pgtable.c:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81086c90-ffffffff81086cbf: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087a55)
Location: arch/x86/mm/pgtable.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81087980-ffffffff810879af: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089e95)
Location: arch/x86/mm/pgtable.c:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81089dc0-ffffffff81089def: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a115)
Location: arch/x86/mm/pgtable.c:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8108a040-ffffffff8108a06f: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108ad75)
Location: arch/x86/mm/pgtable.c:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8108aca0-ffffffff8108accf: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a315)
Location: arch/x86/mm/pgtable.c:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8109a240-ffffffff8109a26f: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad465)
Location: arch/x86/mm/pgtable.c:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810ad380-ffffffff810ad3b5: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7595)
Location: arch/x86/mm/pgtable.c:545
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810c7480-ffffffff810c74b5: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cace5)
Location: arch/x86/mm/pgtable.c:545
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810cabd0-ffffffff810cac05: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3235)
Location: arch/x86/mm/pgtable.c:557
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810d3120-ffffffff810d3155: ptep_test_and_clear_young (STB_GLOBAL)
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
In mm/pgtable-generic.c (ffff8000103080b4)
Location: arch/arm64/include/asm/pgtable.h:718
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309d28)
Location: arch/arm64/include/asm/pgtable.h:718
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_idle.c (ffff8000103795d4)
Location: arch/arm64/include/asm/pgtable.h:718
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffff80001043aa10)
Location: arch/arm64/include/asm/pgtable.h:718
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
In mm/pgtable-generic.c (c0525540)
Location: include/asm-generic/pgtable.h:62
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
```
In mm/page_idle.c (c05643fc)
Location: include/asm-generic/pgtable.h:62
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (c0600428)
Location: include/asm-generic/pgtable.h:62
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/rmap.c (ffffffe000213cfe)
Location: arch/riscv/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/page_idle.c (ffffffe000250776)
Location: arch/riscv/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffffffe0002d22b4)
Location: arch/riscv/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086a55)
Location: arch/x86/mm/pgtable.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81086980-ffffffff810869af: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810756e5)
Location: arch/x86/mm/pgtable.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81075610-ffffffff8107563f: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086a05)
Location: arch/x86/mm/pgtable.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81086930-ffffffff8108695f: ptep_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088b35)
Location: arch/x86/mm/pgtable.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81088a60-ffffffff81088a8f: ptep_test_and_clear_young (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
