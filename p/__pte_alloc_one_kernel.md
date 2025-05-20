# Function: <code>__pte_alloc_one_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81250175)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff8125e725)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff8128e745)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff81299365)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff8129e5f5)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
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
In mm/memory.c (ffffffff812df835)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8132c203)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
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
In mm/memory.c (ffffffff8133fd85)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8139bd1d)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff813b7cd5)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413602)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff813eca45)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446b62)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff81417f35)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480a96)
Location: include/asm-generic/pgalloc.h:19
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
In virt/kvm/arm/mmu.c (ffff8000100c8ee0)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In mm/memory.c (ffff8000102f610c)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (c05180e8)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020732a)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff81256d75)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff81249715)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff81254b15)
Location: include/asm-generic/pgalloc.h:19
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
In mm/memory.c (ffffffff81264595)
Location: include/asm-generic/pgalloc.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
</details>
</li>
</ul>

## Differences
