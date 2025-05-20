# Function: <code>get_kernel_context</code>

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
In arch/powerpc/kernel/process.c (c0000000000222a0)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:copy_thread_tls
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008bcd4)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hpte_do_hugepage_flush
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008d2f8)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_bolt_mapping
```
```
In arch/powerpc/mm/book3s64/slb.c (c00000000008fe98)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:do_slb_fault
  - arch/powerpc/mm/book3s64/slb.c:slb_initialize
  - arch/powerpc/mm/book3s64/slb.c:slb_initialize
  - arch/powerpc/mm/book3s64/slb.c:slb_initialize
  - arch/powerpc/mm/book3s64/slb.c:slb_initialize
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (c0000000000918f4)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:hpte_need_flush
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000093cf4)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_removebolted
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_updateboltedpp
```
```
In arch/powerpc/mm/copro_fault.c (c0000000000a68d4)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/mm/copro_fault.c:copro_calculate_slb
  - arch/powerpc/mm/copro_fault.c:copro_calculate_slb
  - arch/powerpc/mm/copro_fault.c:copro_calculate_slb
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000ea314)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:811
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_hpte_removebolted
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_hpte_updateboltedpp
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
