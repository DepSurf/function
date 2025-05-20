# Function: <code>hpte_new_to_old_r</code>

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
In arch/powerpc/mm/book3s64/hash_native.c (0)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:369
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000012041c)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:369
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_hpte_hv_fault
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_hv_find_lock_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_clear_ref_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_invalidate_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_read
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_bulk_remove
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_remove
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
