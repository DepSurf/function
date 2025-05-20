# Function: <code>cc_mkdec</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 cc_mkdec(u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002a40)
Location: arch/x86/coco/core.c:118
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
  - kernel/dma/direct.c:dma_direct_mmap
  - mm/memory.c:vm_iomap_memory
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
```
**Symbols:**

```
ffffffff81002a40-ffffffff81002a82: cc_mkdec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 cc_mkdec(u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81003380)
Location: arch/x86/coco/core.c:118
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
  - kernel/dma/direct.c:dma_direct_mmap
  - mm/memory.c:vm_iomap_memory
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff81003380-ffffffff810033c2: cc_mkdec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 cc_mkdec(u64 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002a20)
Location: arch/x86/coco/core.c:135
Inline: True
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
  - kernel/dma/direct.c:dma_direct_mmap
  - mm/memory.c:vm_iomap_memory
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff81002a20-ffffffff81002a73: cc_mkdec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 cc_mkdec(u64 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002a70)
Location: arch/x86/coco/core.c:135
Inline: True
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_map_gpa
  - arch/x86/coco/tdx/tdx.c:tdx_map_gpa
  - arch/x86/coco/tdx/tdx.c:tdx_hcall_get_quote
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
  - kernel/dma/direct.c:dma_direct_mmap
  - mm/memory.c:vm_iomap_memory
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
```
**Symbols:**

```
ffffffff81002a70-ffffffff81002ac3: cc_mkdec (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
