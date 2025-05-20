# Function: <code>kvm_is_radix</code>

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
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000119200)
Location: arch/powerpc/include/asm/kvm_book3s_64.h:138
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_stuff_tce
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011ffe0)
Location: arch/powerpc/include/asm/kvm_book3s_64.h:138
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_mod
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_ref
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_read
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_protect
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_bulk_remove
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_remove
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000120e74)
Location: arch/powerpc/include/asm/kvm_book3s_64.h:138
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_check_need_tlb_flush
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_h_random
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
