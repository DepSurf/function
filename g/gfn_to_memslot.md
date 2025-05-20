# Function: <code>gfn_to_memslot</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct kvm_memory_slot *gfn_to_memslot(struct kvm *kvm, gfn_t gfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b8c2c)
Location: virt/kvm/kvm_main.c:1374
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:mark_page_dirty
  - virt/kvm/kvm_main.c:kvm_write_guest_page
  - virt/kvm/kvm_main.c:kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_unmap_gfn
  - virt/kvm/kvm_main.c:gfn_to_pfn
  - virt/kvm/kvm_main.c:gfn_to_pfn_atomic
  - virt/kvm/kvm_main.c:gfn_to_pfn_prot
  - virt/kvm/kvm_main.c:gfn_to_hva_prot
  - virt/kvm/kvm_main.c:gfn_to_hva
  - virt/kvm/kvm_main.c:kvm_is_visible_gfn
Direct callers:
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
```
**Symbols:**

```
ffff8000100b89a0-ffff8000100b8a88: gfn_to_memslot (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
