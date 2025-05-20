# Function: <code>get_user_vsid</code>

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
In <code>arm64</code>: Absent ⚠️
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
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008bbf0)
Location: arch/powerpc/include/asm/book3s/64/mmu.h:258
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hpte_do_hugepage_flush
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dd34)
Location: arch/powerpc/include/asm/book3s/64/mmu.h:258
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (c0000000000916d8)
Location: arch/powerpc/include/asm/book3s/64/mmu.h:258
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:hpte_need_flush
```
```
In arch/powerpc/mm/copro_fault.c (c0000000000a6984)
Location: arch/powerpc/include/asm/book3s/64/mmu.h:258
Inline: True
Inline callers:
  - arch/powerpc/mm/copro_fault.c:copro_calculate_slb
```
</details>
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
