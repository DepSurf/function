# Function: <code>cachemode2protval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81f7790e)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e84f)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_pages_array
```
```
In arch/x86/mm/pat.c (ffffffff81070402)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_insert
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In drivers/base/dma-mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In drivers/usb/early/ehci-dbgp.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In drivers/vme/vme.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
```
In arch/x86/pci/i386.c (0)
Location: arch/x86/include/asm/pgtable_types.h:345
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a0fc)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058124)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81fa0043)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8106ba51)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e956)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff8106f695)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bad12)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff8156bf75)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/base/dma-mapping.c (ffffffff815b1c03)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fdd836)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
```
```
In drivers/vme/vme.c (ffffffff81755706)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
```
In arch/x86/pci/i386.c (ffffffff8175b24f)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd55d6)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105aeb4)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81fdb5ad)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f671)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pageattr.c (ffffffff810725f5)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff810732c5)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dcd12)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff815986e5)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/base/dma-mapping.c (ffffffff815e0e53)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8201b44d)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
```
```
In drivers/vme/vme.c (ffffffff81781cc6)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
```
In arch/x86/pci/i386.c (ffffffff817877d8)
Location: arch/x86/include/asm/pgtable_types.h:383
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b6307)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a46d)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff820bc5cb)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8106ed83)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pageattr.c (ffffffff81071bd1)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff810728c5)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In drivers/pci/mmap.c (ffffffff814b90b7)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e88a8)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff815ac535)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/base/dma-mapping.c (ffffffff815f5cc3)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff820fdce8)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
```
```
In drivers/vme/vme.c (ffffffff817a0a86)
Location: arch/x86/include/asm/pgtable_types.h:420
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bcb03)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e96d)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff826c3005)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81073e7a)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81077271)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81078225)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In drivers/pci/mmap.c (ffffffff814f9507)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151d3bc)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff81612ef5)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/base/dma-mapping.c (ffffffff8165dbe3)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff827075d4)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
```
```
In drivers/vme/vme.c (ffffffff81817b66)
Location: arch/x86/include/asm/pgtable_types.h:445
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e68bb)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106194a)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff826ed271)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81076898)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81079cda)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff8107ad85)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (ffffffff8110c604)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In drivers/pci/mmap.c (ffffffff81529fc8)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8155312a)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff8164ccb5)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff827314c1)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff818616b8)
Location: arch/x86/include/asm/pgtable_types.h:444
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289d404)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106762a)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828a3e03)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8107cef0)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff810804ea)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff810816c5)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (ffffffff81118404)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In drivers/pci/mmap.c (ffffffff8153fe87)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156a9aa)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff8166ae35)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ea183)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff81880e48)
Location: arch/x86/include/asm/pgtable_types.h:468
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b54b2)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106add3)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828bc2aa)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff810805fa)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81083faa)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81085365)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
```
```
In drivers/pci/mmap.c (ffffffff8156f770)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159b105)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff816a09d8)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82904ba4)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff818cb411)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b891c)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b773)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828c2751)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8108182d)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81084cea)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81086055)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
```
```
In drivers/pci/mmap.c (ffffffff8159079e)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bc4e5)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff816c3778)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d60b8)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290e5ea)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff818fd801)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81084040)
Location: arch/x86/mm/init.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/hpet.c:hpet_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/vme/vme.c:vme_master_mmap
```
**Symbols:**

```
ffffffff81084040-ffffffff8108405d: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810855b0)
Location: arch/x86/mm/init.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/hpet.c:hpet_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/vme/vme.c:vme_master_mmap
```
**Symbols:**

```
ffffffff810855b0-ffffffff810855cd: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810862b0)
Location: arch/x86/mm/init.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/hpet.c:hpet_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/vme/vme.c:vme_master_mmap
```
**Symbols:**

```
ffffffff810862b0-ffffffff810862cd: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810954a0)
Location: arch/x86/mm/init.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/hpet.c:hpet_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/vme/vme.c:vme_master_mmap
```
**Symbols:**

```
ffffffff810954a0-ffffffff810954d7: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810a7850)
Location: arch/x86/mm/init.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/hpet.c:hpet_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/vme/vme.c:vme_master_mmap
```
**Symbols:**

```
ffffffff810a7850-ffffffff810a7897: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c0bf0)
Location: arch/x86/mm/init.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/hpet.c:hpet_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/staging/vme_user/vme.c:vme_master_mmap
```
**Symbols:**

```
ffffffff810c0bf0-ffffffff810c0c37: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c42d0)
Location: arch/x86/mm/init.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/char/hpet.c:hpet_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/staging/vme_user/vme.c:vme_master_mmap
  - arch/x86/video/fbdev.c:fb_pgprotect
```
**Symbols:**

```
ffffffff810c42d0-ffffffff810c4317: cachemode2protval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810cc720)
Location: arch/x86/mm/init.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_set_fixmap
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/memtype.c:pgprot_writethrough
  - arch/x86/mm/pat/memtype.c:pgprot_writecombine
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed
  - mm/memremap.c:memremap_pages
  - drivers/pci/mmap.c:pci_mmap_resource_range
  - drivers/char/hpet.c:hpet_mmap
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/staging/vme_user/vme.c:vme_master_mmap
  - arch/x86/video/fbdev.c:pgprot_framebuffer
```
**Symbols:**

```
ffffffff810cc720-ffffffff810cc767: cachemode2protval (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a6923)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b263)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828ad727)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8108082d)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81083cea)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81085055)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
```
```
In drivers/pci/mmap.c (ffffffff81584630)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b0635)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff816891c8)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828f5744)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff8189eb31)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289ea43)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b5a3)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828a59e8)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f77d)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff8107293a)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81073d25)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
```
```
In drivers/pci/mmap.c (ffffffff815733fe)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159f7c5)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff81666c58)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780168)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ed058)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff8185a2a1)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b9833)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b713)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828c0626)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff810807dd)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81083c9a)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81085005)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
```
```
In drivers/pci/mmap.c (ffffffff815844ee)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b0bc5)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff816b7438)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817caf38)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff829099e5)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff818ee221)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b9934)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ce13)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff828c3771)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff810828fd)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
```
```
In arch/x86/mm/pageattr.c (ffffffff81085dda)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
```
In arch/x86/mm/pat.c (ffffffff81087155)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pgprot_writethrough
  - arch/x86/mm/pat.c:pgprot_writecombine
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:phys_mem_access_prot_allowed
```
```
In kernel/dma/mapping.c (0)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
```
```
In drivers/pci/mmap.c (ffffffff8159e99e)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815ca635)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
```
In drivers/char/hpet.c (ffffffff816d1b98)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_mmap
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e51d8)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290f64c)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
```
In drivers/vme/vme.c (ffffffff8190f411)
Location: arch/x86/include/asm/pgtable_types.h:467
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_mmap
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
