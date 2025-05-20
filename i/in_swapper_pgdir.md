# Function: <code>in_swapper_pgdir</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/mm/mmu.c (ffff80001143827c)
Location: arch/arm64/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:alloc_init_pud
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca1a8)
Location: arch/arm64/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_get_pud
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f98c8)
Location: arch/arm64/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307ee8)
Location: arch/arm64/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffff800010da0fd4)
Location: arch/arm64/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
</details>
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
