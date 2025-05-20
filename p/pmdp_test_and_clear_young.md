# Function: <code>pmdp_test_and_clear_young</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071000)
Location: arch/x86/mm/pgtable.c:463
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81071000-ffffffff8107104a: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070f88)
Location: arch/x86/mm/pgtable.c:466
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810709a0-ffffffff810709b6: pmdp_test_and_clear_young.part.10 (STB_LOCAL)
ffffffff81070f30-ffffffff81070f69: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074b08)
Location: arch/x86/mm/pgtable.c:466
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81074630-ffffffff81074646: pmdp_test_and_clear_young.part.12 (STB_LOCAL)
ffffffff81074ab0-ffffffff81074ae9: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810740d8)
Location: arch/x86/mm/pgtable.c:496
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81073b80-ffffffff81073b96: pmdp_test_and_clear_young.part.13 (STB_LOCAL)
ffffffff81074040-ffffffff8107407a: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079b6f)
Location: arch/x86/mm/pgtable.c:493
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81079a80-ffffffff81079ad0: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c640)
Location: arch/x86/mm/pgtable.c:498
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8107c640-ffffffff8107c685: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81083050)
Location: arch/x86/mm/pgtable.c:564
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81083050-ffffffff81083095: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086cc0)
Location: arch/x86/mm/pgtable.c:551
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81086cc0-ffffffff81086d04: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810879b0)
Location: arch/x86/mm/pgtable.c:547
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810879b0-ffffffff810879f4: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089ec5)
Location: arch/x86/mm/pgtable.c:554
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81089df0-ffffffff81089e37: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a145)
Location: arch/x86/mm/pgtable.c:554
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8108a070-ffffffff8108a0b7: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108ada5)
Location: arch/x86/mm/pgtable.c:554
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8108acd0-ffffffff8108ad14: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a345)
Location: arch/x86/mm/pgtable.c:554
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8109a270-ffffffff8109a2b4: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad4a5)
Location: arch/x86/mm/pgtable.c:554
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810ad3c0-ffffffff810ad40e: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c75e5)
Location: arch/x86/mm/pgtable.c:558
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810c74d0-ffffffff810c751e: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cad35)
Location: arch/x86/mm/pgtable.c:558
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810cac20-ffffffff810cac6e: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3285)
Location: arch/x86/mm/pgtable.c:570
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
Direct callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810d3170-ffffffff810d31be: pmdp_test_and_clear_young (STB_GLOBAL)
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
Location: arch/arm64/include/asm/pgtable.h:748
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/page_idle.c (ffff800010379678)
Location: arch/arm64/include/asm/pgtable.h:748
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffff80001043aa10)
Location: arch/arm64/include/asm/pgtable.h:748
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090a20)
Location: arch/powerpc/mm/book3s64/pgtable.c:55
Inline: False
Direct callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
c000000000090a20-c000000000090ab4: pmdp_test_and_clear_young (STB_GLOBAL)
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
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:91
Inline: True
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
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810869b0)
Location: arch/x86/mm/pgtable.c:547
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff810869b0-ffffffff810869f4: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075640)
Location: arch/x86/mm/pgtable.c:547
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81075640-ffffffff81075684: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086960)
Location: arch/x86/mm/pgtable.c:547
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81086960-ffffffff810869a4: pmdp_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088a90)
Location: arch/x86/mm/pgtable.c:547
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81088a90-ffffffff81088ad4: pmdp_test_and_clear_young (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
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
