# Function: <code>pte_free_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd44f)
Location: arch/x86/include/asm/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d81cc)
Location: arch/x86/include/asm/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7e9c)
Location: arch/x86/include/asm/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f302f)
Location: arch/x86/include/asm/pgalloc.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120a1a9)
Location: arch/x86/include/asm/pgalloc.h:56
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122afcc)
Location: arch/x86/include/asm/pgalloc.h:56
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123e38c)
Location: arch/x86/include/asm/pgalloc.h:56
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81250237)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125e7e7)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128e807)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81299427)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e6c1)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812df901)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
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
In mm/memory.c (ffffffff8133fe74)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8139becc)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
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
In mm/memory.c (ffffffff813b7dc4)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff814137ca)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
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
In mm/memory.c (ffffffff813ecb34)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446d22)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
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
In mm/memory.c (ffffffff81418045)
Location: include/asm-generic/pgalloc.h:47
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480ca4)
Location: include/asm-generic/pgalloc.h:47
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
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
In arch/arm64/mm/mmu.c (ffff8000100ae48c)
Location: include/asm-generic/pgalloc.h:42
Inline: True
```
```
In virt/kvm/arm/mmu.c (ffff8000100c9580)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
```
```
In mm/memory.c (ffff8000102f61e4)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
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
In mm/memory.c (c0518198)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095b90)
Location: arch/powerpc/include/asm/pgalloc.h:38
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_free_pte_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In mm/memory.c (c0000000003bdb20)
Location: arch/powerpc/include/asm/pgalloc.h:38
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
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
In mm/memory.c (ffffffe0002073b0)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256e37)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124978f)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254bd7)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264665)
Location: include/asm-generic/pgalloc.h:42
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
</ul>

## Differences
