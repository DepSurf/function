# Function: <code>memblock_alloc_try_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b386)
Location: mm/memblock.c:1215
Inline: False
```
**Symbols:**

```
ffffffff81f8b386-ffffffff81f8b3af: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4fca)
Location: mm/memblock.c:1216
Inline: False
```
**Symbols:**

```
ffffffff81fb4fca-ffffffff81fb4ff3: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff19b1)
Location: mm/memblock.c:1216
Inline: False
```
**Symbols:**

```
ffffffff81ff19b1-ffffffff81ff19da: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3e18)
Location: mm/memblock.c:1240
Inline: False
```
**Symbols:**

```
ffffffff820d3e18-ffffffff820d3e46: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc827)
Location: mm/memblock.c:1212
Inline: False
```
**Symbols:**

```
ffffffff826dc827-ffffffff826dc855: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706d66)
Location: mm/memblock.c:1220
Inline: False
```
**Symbols:**

```
ffffffff82706d66-ffffffff82706d94: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828be0bd)
Location: mm/memblock.c:1534
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828be0bd-ffffffff828be16b: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d72b5)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828d72b5-ffffffff828d733e: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df726)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828df726-ffffffff828df7af: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfccdf)
Location: mm/memblock.c:1593
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/apic/io_apic.c:ioapic_setup_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff82cfccdf-ffffffff82cfcd6b: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe9762)
Location: mm/memblock.c:1555
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/apic/io_apic.c:ioapic_setup_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
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
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff82fe9762-ffffffff82fe97ee: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3e0b)
Location: mm/memblock.c:1556
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:setup_boot_config
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
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
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff831f3e0b-ffffffff831f3e97: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832da151)
Location: mm/memblock.c:1579
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:setup_boot_config
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
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
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/core.c:kfence_alloc_pool
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff832da151-ffffffff832da1dd: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f1cf)
Location: mm/memblock.c:1586
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
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
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:free_area_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/core.c:kfence_alloc_pool
  - lib/stackdepot.c:stack_depot_early_init
  - lib/bootconfig.c:xbc_alloc_mem
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff8348f1cf-ffffffff8348f26d: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec16a0)
Location: mm/memblock.c:1604
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
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
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:free_area_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/core.c:kfence_alloc_pool
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff83ec16a0-ffffffff83ec1745: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6eb0)
Location: mm/memblock.c:1626
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:free_area_init
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
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
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/core.c:kfence_alloc_pool
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff836e6eb0-ffffffff836e6f55: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83919460)
Location: mm/memblock.c:1684
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - init/main.c:print_unknown_bootoptions
  - init/main.c:setup_command_line
  - init/main.c:setup_command_line
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/mm_init.c:alloc_large_system_hash
  - mm/mm_init.c:free_area_init
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
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
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - mm/kfence/core.c:kfence_alloc_pool_and_metadata
  - mm/kfence/core.c:kfence_alloc_pool_and_metadata
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff83919460-ffffffff83919505: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001145877c)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/mm/numa.c:pcpu_fc_alloc
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/firmware/memmap.c:firmware_map_add_early
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
ffff80001145877c-ffff800011458820: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c15326d4)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/mm/mmu.c:vm_reserve_area_early
  - arch/arm/mm/mmu.c:iotable_init
  - arch/arm/mm/mmu.c:early_alloc
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - mm/percpu.c:pcpu_dfl_fc_alloc
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_ext.c:page_ext_init_flatmem
  - drivers/clk/ti/clk.c:omap2_clk_legacy_provider_init
  - drivers/firmware/memmap.c:firmware_map_add_early
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
c15326d4-c1532788: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c000000001381fa4)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup_64.c:init_fallback_flush
  - arch/powerpc/kernel/setup_64.c:pcpu_fc_alloc
  - arch/powerpc/kernel/setup_64.c:alloc_stack
  - arch/powerpc/kernel/paca.c:allocate_paca
  - arch/powerpc/kernel/paca.c:alloc_paca_data
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/mm/book3s64/pgtable.c:mmu_partition_table_init
  - arch/powerpc/mm/book3s64/radix_pgtable.c:early_alloc_pgtable
  - arch/powerpc/lib/alloc.c:zalloc_maybe_bootmem
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc
  - arch/powerpc/platforms/powernv/setup.c:pnv_probe
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
c000000001381fa4-c00000000138206c: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016e4e)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:pcpu_dfl_fc_alloc
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/of/fdt.c:early_init_dt_alloc_memory_arch
```
**Symbols:**

```
ffffffe000016e4e-ffffffe000016ee2: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c85da)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828c85da-ffffffff828c8663: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0cff)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828c0cff-ffffffff828c0d88: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db35a)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828db35a-ffffffff828db3e3: memblock_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memblock_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e077b)
Location: mm/memblock.c:1539
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/tce_64.c:alloc_tce_table
  - arch/x86/mm/init_64.c:spp_getpage
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/percpu.c:memblock_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff828e077b-ffffffff828e0804: memblock_alloc_try_nid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t min_addr</code>
</li>
<li>
<b>Param added. </b>
<code>phys_addr_t max_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>size, align, nid</code> ➡️ <code>size, align, min_addr, max_addr, nid</code>
</li>
<li>
<b>Return type changed. </b>
<code>phys_addr_t</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
