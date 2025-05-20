# Function: <code>kvm_vcpu_gfn_to_memslot</code>

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
struct kvm_memory_slot *kvm_vcpu_gfn_to_memslot(struct kvm_vcpu *vcpu, gfn_t gfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b8d24)
Location: virt/kvm/kvm_main.c:1380
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_mark_page_dirty
  - virt/kvm/kvm_main.c:kvm_vcpu_write_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_unmap
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn_atomic
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva_prot
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva
```
**Symbols:**

```
ffff8000100bd5d8-ffff8000100bd6c4: kvm_vcpu_gfn_to_memslot (STB_GLOBAL)
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
