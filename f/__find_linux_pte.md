# Function: <code>__find_linux_pte</code>

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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pte_t *__find_linux_pte(pgd_t *pgdir, long unsigned int ea, bool *is_thp, unsigned int *hpage_shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable.c (c000000000087900)
Location: arch/powerpc/mm/pgtable.c:312
Inline: False
Direct callers:
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_offset
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr
  - arch/powerpc/perf/callchain.c:read_user_stack_slow
```
**Symbols:**

```
c000000000087900-c000000000087c24: __find_linux_pte (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
