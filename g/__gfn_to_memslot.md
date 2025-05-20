# Function: <code>__gfn_to_memslot</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b8d3c)
Location: include/linux/kvm_host.h:1040
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_mark_page_dirty
  - virt/kvm/kvm_main.c:mark_page_dirty
  - virt/kvm/kvm_main.c:__kvm_gfn_to_hva_cache_init
  - virt/kvm/kvm_main.c:kvm_vcpu_write_guest_page
  - virt/kvm/kvm_main.c:kvm_write_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_page
  - virt/kvm/kvm_main.c:kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_unmap
  - virt/kvm/kvm_main.c:kvm_unmap_gfn
  - virt/kvm/kvm_main.c:__kvm_map_gfn
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn
  - virt/kvm/kvm_main.c:gfn_to_pfn
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn_atomic
  - virt/kvm/kvm_main.c:gfn_to_pfn_atomic
  - virt/kvm/kvm_main.c:gfn_to_pfn_prot
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva_prot
  - virt/kvm/kvm_main.c:gfn_to_hva_prot
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva
  - virt/kvm/kvm_main.c:gfn_to_hva
  - virt/kvm/kvm_main.c:kvm_is_visible_gfn
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011c970)
Location: include/linux/kvm_host.h:1040
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_mod
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:revmap_for_hpte
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
