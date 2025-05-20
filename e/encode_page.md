# Function: <code>encode_page</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b858d)
Location: include/linux/mm_types.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/memory.c (ffffffff813b8c5e)
Location: include/linux/mm_types.h:273
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/hugetlb.c (ffffffff8140fbee)
Location: include/linux/mm_types.h:273
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff8143fd84)
Location: include/linux/mm_types.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810bb78d)
Location: include/linux/mm_types.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/memory.c (ffffffff813ed8a6)
Location: include/linux/mm_types.h:249
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/hugetlb.c (ffffffff81442fb5)
Location: include/linux/mm_types.h:249
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814755af)
Location: include/linux/mm_types.h:249
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810c2ba2)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_tlb_remove_table
```
```
In mm/memory.c (ffffffff81418e9b)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/hugetlb.c (ffffffff8147d1cc)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814a4fa7)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
