# Function: <code>gfn_to_hva_memslot_prot</code>

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
long unsigned int gfn_to_hva_memslot_prot(struct kvm_memory_slot *slot, gfn_t gfn, bool *writable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100bd6c8)
Location: virt/kvm/kvm_main.c:1474
Inline: True
Direct callers:
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva_prot
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva_prot
  - virt/kvm/kvm_main.c:gfn_to_hva_prot
  - virt/kvm/kvm_main.c:gfn_to_hva_prot
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
```
**Symbols:**

```
ffff8000100bd6c8-ffff8000100bd730: gfn_to_hva_memslot_prot (STB_GLOBAL)
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
