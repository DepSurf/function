# Function: <code>pmd_free</code>

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
Location: arch/x86/include/asm/pgalloc.h:94
Inline: True
```
```
In mm/memory.c (ffffffff811beb35)
Location: arch/x86/include/asm/pgalloc.h:94
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
Location: arch/x86/include/asm/pgalloc.h:98
Inline: True
```
```
In mm/memory.c (ffffffff811da97e)
Location: arch/x86/include/asm/pgalloc.h:98
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
Location: arch/x86/include/asm/pgalloc.h:98
Inline: True
```
```
In mm/memory.c (ffffffff811ea4eb)
Location: arch/x86/include/asm/pgalloc.h:98
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
Location: arch/x86/include/asm/pgalloc.h:100
Inline: True
```
```
In mm/memory.c (ffffffff811f55db)
Location: arch/x86/include/asm/pgalloc.h:100
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
```
```
In mm/memory.c (ffffffff8120e4c0)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
```
```
In mm/memory.c (ffffffff8122eede)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:119
Inline: True
```
```
In mm/memory.c (ffffffff8124196e)
Location: arch/x86/include/asm/pgalloc.h:119
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
```
```
In mm/memory.c (ffffffff812542ed)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
```
```
In mm/memory.c (ffffffff8126284d)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: False
```
```
In mm/memory.c (ffffffff8129274d)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:138
Inline: False
```
```
In mm/memory.c (ffffffff8129d033)
Location: include/asm-generic/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:138
Inline: False
```
```
In mm/memory.c (ffffffff812a2715)
Location: include/asm-generic/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:138
Inline: False
```
```
In mm/memory.c (ffffffff812e3a85)
Location: include/asm-generic/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:138
Inline: False
```
```
In mm/memory.c (ffffffff81344e28)
Location: include/asm-generic/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:138
Inline: False
```
```
In mm/memory.c (ffffffff813bd058)
Location: include/asm-generic/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:138
Inline: False
```
```
In mm/memory.c (ffffffff813f1d9e)
Location: include/asm-generic/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgalloc.h:146
Inline: False
```
```
In mm/memory.c (ffffffff8141ca1e)
Location: include/asm-generic/pgalloc.h:146
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/arm64/mm/mmu.c (ffff8000100af564)
Location: arch/arm64/include/asm/pgalloc.h:40
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
```
```
In virt/kvm/arm/mmu.c (ffff8000100c962c)
Location: arch/arm64/include/asm/pgalloc.h:40
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
```
```
In mm/memory.c (ffff8000102f9ab0)
Location: arch/arm64/include/asm/pgalloc.h:40
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095a30)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:136
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In mm/memory.c (c0000000003c39d0)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:136
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In mm/memory.c (ffffffe0002097f6)
Location: arch/riscv/include/asm/pgalloc.h:70
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
```
```
In mm/memory.c (ffffffff8125ae9d)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
```
```
In mm/memory.c (ffffffff8124d1dd)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
```
```
In mm/memory.c (ffffffff81258c3d)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
```
```
In mm/memory.c (ffffffff8126863b)
Location: arch/x86/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
</ul>

## Differences
