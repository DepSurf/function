# Function: <code>__kvm_memslots</code>

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
In virt/kvm/kvm_main.c (ffff8000100b8d2c)
Location: include/linux/kvm_host.h:626
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_mark_page_dirty
  - virt/kvm/kvm_main.c:mark_page_dirty
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:kvm_gfn_to_hva_cache_init
  - virt/kvm/kvm_main.c:kvm_vcpu_write_guest_page
  - virt/kvm/kvm_main.c:kvm_write_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_page
  - virt/kvm/kvm_main.c:kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_unmap
  - virt/kvm/kvm_main.c:kvm_unmap_gfn
  - virt/kvm/kvm_main.c:kvm_vcpu_map
  - virt/kvm/kvm_main.c:kvm_map_gfn
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
  - virt/kvm/kvm_main.c:kvm_clear_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100c82fc)
Location: include/linux/kvm_host.h:626
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:handle_hva_to_gpa
  - virt/kvm/arm/mmu.c:kvm_mmu_wp_memory_region
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
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
