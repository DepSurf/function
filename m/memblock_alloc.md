# Function: <code>memblock_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b379)
Location: mm/memblock.c:1210
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81f8b379-ffffffff81f8b386: memblock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4fbd)
Location: mm/memblock.c:1211
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81fb4fbd-ffffffff81fb4fca: memblock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff19a4)
Location: mm/memblock.c:1211
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff81ff19a4-ffffffff81ff19b1: memblock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3e06)
Location: mm/memblock.c:1235
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff820d3e06-ffffffff820d3e18: memblock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc815)
Location: mm/memblock.c:1207
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff826dc815-ffffffff826dc827: memblock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706d54)
Location: mm/memblock.c:1215
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff82706d54-ffffffff82706d66: memblock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82882b0e)
Location: include/linux/memblock.h:343
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/p2m.c (ffffffff81a1f8d0)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff828922cd)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828996d5)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ebe5)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81a20509)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828ad349)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828ad8da)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828af038)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828bb5d2)
Location: include/linux/memblock.h:343
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff828bfbcb)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a2329f)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In lib/cpumask.c (ffffffff828fdfff)
Location: include/linux/memblock.h:343
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82882b0e-ffffffff82882b26: memblock_alloc.constprop.9 (STB_LOCAL)
ffffffff828bb5d2-ffffffff828bb5ea: memblock_alloc.constprop.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82899a93)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/p2m.c (ffffffff81a900a0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff828a97fa)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b13b7)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b6af0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81a90a99)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828c5ce8)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828c6292)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828c7b7e)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828d270a)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff828d6f17)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff828d8f0f)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a93417)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff829050d2)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff8290d048)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff8291ac36)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82899a93-ffffffff82899aab: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff828d270a-ffffffff828d271d: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff8289ca93)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/p2m.c (ffffffff81ac7430)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff828ac85e)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b4806)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9fc5)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81ac7e19)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828ce32c)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828ce8bf)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828d015b)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828dab7c)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff828df388)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff828e1362)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acab7d)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290eb0d)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff82916a1b)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff82924aa5)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8289ca93-ffffffff8289caab: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff828dab7c-ffffffff828dab8f: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82cc2c24)
Location: include/linux/memblock.h:374
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff81bbfeb0)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff82cd1ba7)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9e51)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdeb07)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_setup_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81bc090d)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff82cef74a)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff82cefd25)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff82cf1492)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff82cf8e89)
Location: include/linux/memblock.h:374
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff82cfc732)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff82cfe9c3)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In lib/bootconfig.c (ffffffff82d0a5bb)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
```
```
In lib/cpumask.c (ffffffff82d0a8b5)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81bc308c)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22d0b)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff82d28e57)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff82cc2c24-ffffffff82cc2c3c: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff82cf8e89-ffffffff82cf8e9c: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faefb8)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff81c38e40)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff82fbd9f7)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc57fc)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcac9e)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_setup_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev-es.c (ffffffff82fd12a7)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff81c3997e)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff82fdbe75)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff82fdc5ad)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff82fdded3)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff82fe5c4b)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff82fe914d)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff82feb2f3)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In lib/bootconfig.c (ffffffff82ff7ba2)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
```
```
In lib/cpumask.c (ffffffff82ff7ea9)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81c3bd01)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff830109ac)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff8301756f)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b91f0)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:setup_boot_config
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff81c2b200)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff831c810b)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff831d006f)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5eaf)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev.c (ffffffff831dbf5c)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff81c2be0e)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff831e6bd8)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff831e730f)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff831e8a09)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff831f04ea)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/page_alloc.c (ffffffff831f397f)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff831f5c5a)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In lib/bootconfig.c (ffffffff832026b2)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
```
```
In lib/cpumask.c (ffffffff83202b20)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8320fe35)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8321b8c9)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff8322244e)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83299223)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:setup_boot_config
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff81d49870)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff832a9349)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2afb)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8b12)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev.c (ffffffff832befc5)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff81d4a59b)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff832cad52)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - kernel/power/snapshot.c:register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff832cb498)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff832ccf6f)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff832d5e20)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/page_alloc.c (ffffffff832d9c7b)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff832dc334)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In mm/kfence/core.c (ffffffff832dcf64)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_alloc_pool
```
```
In lib/bootconfig.c (ffffffff832e9e61)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
```
```
In lib/cpumask.c (ffffffff832ea31c)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
```
In drivers/xen/swiotlb-xen.c (ffffffff832f8df6)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83305518)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff8330c090)
Location: include/linux/memblock.h:408
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83447400)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff81f18d7f)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff834589e6)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff834641cf)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a882)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev.c (ffffffff834712f6)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff81f19bf8)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff8347e334)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - kernel/power/snapshot.c:register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff8347eb7b)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff83480a6f)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In mm/percpu.c (ffffffff8348a6ca)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/page_alloc.c (ffffffff8348ec55)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:free_area_init
```
```
In mm/sparse.c (ffffffff83491b01)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In mm/kfence/core.c (ffffffff8349262a)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_alloc_pool
```
```
In lib/stackdepot.c (ffffffff834a0a9a)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_early_init
```
```
In lib/bootconfig.c (ffffffff834a0bfe)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_alloc_mem
```
```
In lib/cpumask.c (ffffffff834a1c76)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff834be657)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff834c5a06)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e60678)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff820c083f)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff83e77ec5)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff83e86f2d)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f8ae)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev.c (ffffffff83e982fb)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff820c1828)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff83eaa18b)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - kernel/power/snapshot.c:register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff83eaac56)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff83ead213)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In mm/percpu.c (ffffffff83ebb074)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/page_alloc.c (ffffffff83ec0f48)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:free_area_init
```
```
In mm/sparse.c (ffffffff83ec4d2b)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In mm/kfence/core.c (ffffffff83ec62c1)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_alloc_pool
```
```
In lib/bootconfig.c (ffffffff83edb23a)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83efcab1)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/firmware/memmap.c (ffffffff83f06655)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff83f17bf0)
Location: include/linux/memblock.h:424
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83680b78)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff821444ef)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff8369a355)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff836aa4cd)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b314e)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev.c (ffffffff836bbd05)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff821454f8)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff836cf14b)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - kernel/power/snapshot.c:register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff836cfc16)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff836d2273)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In mm/mm_init.c (ffffffff836e2be9)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:free_area_init
```
```
In mm/percpu.c (ffffffff836e36b0)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff836e9e24)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In mm/kfence/core.c (ffffffff836eb35b)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_alloc_pool
```
```
In lib/bootconfig.c (ffffffff83700d6a)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff837228b1)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/firmware/memmap.c (ffffffff8372c675)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff8373e3b0)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838afb78)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
```
```
In arch/x86/xen/p2m.c (ffffffff82226c0f)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff838ca0d5)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff838dac9d)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e3a2e)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/sev.c (ffffffff838ec6e5)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/init_64.c (ffffffff82227c18)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff8390055b)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - kernel/power/snapshot.c:register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff83901026)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff83903fa1)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In mm/mm_init.c (ffffffff839154df)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:free_area_init
```
```
In mm/percpu.c (ffffffff83915f40)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff8391d1e4)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In mm/kfence/core.c (ffffffff8391df11)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_alloc_pool_and_metadata
  - mm/kfence/core.c:kfence_alloc_pool_and_metadata
```
```
In lib/bootconfig.c (ffffffff839345aa)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff839566e1)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/firmware/memmap.c (ffffffff83960695)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff83972dd0)
Location: include/linux/memblock.h:435
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffff8000114309ec)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/arm64/kernel/setup.c (0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In kernel/printk/printk.c (ffff80001144614c)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffff800011447da8)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffff800011453870)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffff800011458198)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffff80001145a4ec)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffff800010d9e1cc)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/firmware/memmap.c (ffff8000114a469c)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In drivers/of/fdt.c (ffff8000114aa450)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
ffff8000114309ec-ffff800011430a10: memblock_alloc.constprop.0 (STB_LOCAL)
ffff800011453870-ffff800011453890: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (c150099c)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/arm/kernel/setup.c (c1504aa4)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/mm/mmu.c (c1508fa8)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:vm_reserve_area_early
  - arch/arm/mm/mmu.c:iotable_init
  - arch/arm/mm/mmu.c:early_alloc
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c15138c4)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
```
```
In kernel/power/snapshot.c (c1520020)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (c15207f4)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/percpu.c (c152e520)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (c1532178)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In drivers/clk/ti/clk.c (c1589dc8)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/clk/ti/clk.c:omap2_clk_legacy_provider_init
```
```
In drivers/firmware/memmap.c (c15a6e3c)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In drivers/of/fdt.c (c15ae968)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
c150099c-c15009cc: memblock_alloc.constprop.0 (STB_LOCAL)
c152e520-c152e54c: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (c0000000013439dc)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a1bc)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/dt_cpu_ftrs.c (c00000000134ee30)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000001356214)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:mmu_partition_table_init
```
```
In arch/powerpc/lib/alloc.c (c0000000000a6dd8)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/lib/alloc.c:zalloc_maybe_bootmem
```
```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7f64)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc
```
```
In arch/powerpc/platforms/powernv/opal.c (c00000000135b8b0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c00000000135fe34)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
```
```
In kernel/printk/printk.c (c00000000136ae10)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (c00000000136ce48)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (c00000000137bdb0)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (c0000000013819b4)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (c000000001384500)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/of/fdt.c (c0000000013ba1a8)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
c0000000013439dc-c000000001343a18: memblock_alloc.constprop.0 (STB_LOCAL)
c00000000137bdb0-c00000000137bde8: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffe0000006e8)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/printk/printk.c (ffffffe000007d22)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffe000009610)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffe000012b26)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffe000016a52)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffe00001862a)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/of/fdt.c (ffffffe00003a818)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
ffffffe0000006e8-ffffffe00000070a: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffe000012b26-ffffffe000012b44: memblock_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff8288aa93)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/p2m.c (ffffffff81a662a0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff8289a870)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828a2825)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7fdd)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81a66c89)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828b7024)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828b75b7)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828b900c)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828c3a30)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff828c823c)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff828ca216)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a699ed)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/firmware/memmap.c (ffffffff828fbf6f)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff829097a9)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8288aa93-ffffffff8288aaab: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff828c3a30-ffffffff828c3a43: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82888a37)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/e820.c (ffffffff82892b2e)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8289a967)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a00b4)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81a23749)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828af2af)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828af842)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828b155d)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828bc155)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff828c0961)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff828c293b)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/firmware/memmap.c (ffffffff828f380b)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff82901af7)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82888a37-ffffffff82888a4f: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff828bc155-ffffffff828bc168: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff8289da93)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/p2m.c (ffffffff81ad26b0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff828ad850)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5722)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baedc)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81ad3099)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828c9f60)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828ca4f3)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828cbd8f)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828d67b0)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff828dafbc)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff828dcf96)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81ad5dfd)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/firmware/memmap.c (ffffffff82911050)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff8291f0f3)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8289da93-ffffffff8289daab: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff828d67b0-ffffffff828d67c3: memblock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *memblock_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff8289da93)
Location: include/linux/memblock.h:368
Inline: True
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/xen/p2m.c (ffffffff81adebb0)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
```
```
In arch/x86/kernel/e820.c (ffffffff828ad86e)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5809)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baff2)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/mm/init_64.c (ffffffff81adf599)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:spp_getpage
```
```
In kernel/power/snapshot.c (ffffffff828cf312)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff828cf8a5)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff828d1189)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff828dbbd1)
Location: include/linux/memblock.h:368
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In mm/page_alloc.c (ffffffff828e03dd)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse.c (ffffffff828e23ad)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81ae22bd)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fb6f)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff82917a7d)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff82925b17)
Location: include/linux/memblock.h:368
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8289da93-ffffffff8289daab: memblock_alloc.constprop.0 (STB_LOCAL)
ffffffff828dbbd1-ffffffff828dbbe4: memblock_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
