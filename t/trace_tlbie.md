# Function: <code>trace_tlbie</code>

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
In arch/powerpc/mm/book3s64/pgtable.c (c0000000000907f4)
Location: arch/powerpc/include/asm/trace.h:188
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:mmu_partition_table_set_entry
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c0000000000927a0)
Location: arch/powerpc/include/asm/trace.h:188
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000097ddc)
Location: arch/powerpc/include/asm/trace.h:188
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_pwc_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_pwc_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_kernel
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_kernel
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_kernel
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_kernel
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__local_flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__local_flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__local_flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__local_flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__local_flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__local_flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_va
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_tlbiel_pid
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
