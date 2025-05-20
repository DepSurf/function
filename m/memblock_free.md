# Function: <code>memblock_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181ea39)
Location: mm/memblock.c:730
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_free_ro_pages
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/mm/numa.c:numa_reset_distance
  - mm/nobootmem.c:free_bootmem_node
  - mm/nobootmem.c:free_bootmem
  - mm/memblock.c:memblock_double_array
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff8181ea39-ffffffff8181ea7e: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898eea)
Location: mm/memblock.c:719
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_free_ro_pages
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/mm/numa.c:numa_reset_distance
  - mm/nobootmem.c:free_bootmem
  - mm/nobootmem.c:free_bootmem_node
  - mm/memblock.c:memblock_double_array
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff81898eea-ffffffff81898f2f: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd592)
Location: mm/memblock.c:719
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_free_ro_pages
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/mm/numa.c:numa_reset_distance
  - mm/nobootmem.c:free_bootmem
  - mm/nobootmem.c:free_bootmem_node
  - mm/memblock.c:memblock_double_array
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff818cd592-ffffffff818cd5d7: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8190499f)
Location: mm/memblock.c:703
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/mm/numa.c:numa_reset_distance
  - mm/nobootmem.c:free_bootmem
  - mm/nobootmem.c:free_bootmem_node
  - mm/memblock.c:memblock_double_array
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff8190499f-ffffffff81904a16: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e9a8)
Location: mm/memblock.c:703
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/kvmclock.c:kvm_memblock_free
  - arch/x86/mm/numa.c:numa_reset_distance
  - mm/nobootmem.c:free_bootmem
  - mm/nobootmem.c:free_bootmem_node
  - mm/memblock.c:memblock_double_array
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff8198e9a8-ffffffff8198ea1f: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb28a)
Location: mm/memblock.c:711
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/kvmclock.c:kvm_memblock_free
  - arch/x86/mm/numa.c:numa_reset_distance
  - mm/nobootmem.c:free_bootmem
  - mm/nobootmem.c:free_bootmem_node
  - mm/memblock.c:memblock_double_array
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff819eb28a-ffffffff819eb301: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a2650a)
Location: mm/memblock.c:819
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_init_nid
  - mm/memory_hotplug.c:__remove_memory
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81a2650a-ffffffff81a26581: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96cb9)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_init_nid
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81a96cb9-ffffffff81a96d32: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace529)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81ace529-ffffffff81ace5a2: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6c47)
Location: mm/memblock.c:812
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - lib/bootconfig.c:xbc_destroy_all
  - lib/cpumask.c:free_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:xdbc_free_ring
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
**Symbols:**

```
ffffffff81bc6c47-ffffffff81bc6cc7: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f969)
Location: mm/memblock.c:799
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_initrd
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - lib/bootconfig.c:xbc_destroy_all
  - lib/cpumask.c:free_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_free_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
**Symbols:**

```
ffffffff81c3f969-ffffffff81c3f9e9: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31a29)
Location: mm/memblock.c:799
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - lib/bootconfig.c:xbc_destroy_all
  - lib/cpumask.c:free_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_free_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
**Symbols:**

```
ffffffff81c31a29-ffffffff81c31aa9: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d5038d)
Location: mm/memblock.c:826
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/mm/init.c:init_mem_mapping
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_free_ptr
  - mm/sparse.c:sparse_buffer_free
  - lib/cpumask.c:free_bootmem_cpumask_var
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_free_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
**Symbols:**

```
ffffffff81d5038d-ffffffff81d5040d: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f20853)
Location: mm/memblock.c:813
Inline: False
Direct callers:
  - init/main.c:print_unknown_bootoptions
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - lib/bootconfig.c:xbc_exit
  - lib/bootconfig.c:xbc_exit
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81f20853-ffffffff81f2089e: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void memblock_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c94f8)
Location: mm/memblock.c:828
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
Direct callers:
  - init/main.c:print_unknown_bootoptions
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/mm/numa.c:numa_init
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff820ca260-ffffffff820ca2a9: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void memblock_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214d758)
Location: mm/memblock.c:841
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
Direct callers:
  - init/main.c:print_unknown_bootoptions
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/mm/numa.c:numa_init
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff8214e4f0-ffffffff8214e539: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void memblock_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82230308)
Location: mm/memblock.c:881
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
Direct callers:
  - init/main.c:print_unknown_bootoptions
  - init/main.c:xbc_make_cmdline
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/mm/numa.c:numa_init
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
  - mm/kfence/core.c:kfence_alloc_pool_and_metadata
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82231260-ffffffff822312a9: memblock_free (STB_GLOBAL)
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
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031cac0)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:free_initrd_mem
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/numa.c:pcpu_fc_free
  - arch/arm64/mm/numa.c:numa_free_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/cma.c:cma_declare_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffff80001031cac0-ffff80001031cb6c: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c05369c8)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:arm_memblock_steal
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - mm/percpu.c:pcpu_dfl_fc_free
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/memblock.c:memblock_double_array
  - mm/cma.c:cma_declare_contiguous
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c05369c8-c0536a78: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0940)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:setup_arch
  - arch/powerpc/kernel/setup_64.c:pcpu_fc_free
  - arch/powerpc/kernel/paca.c:free_unused_pacas
  - arch/powerpc/kernel/paca.c:free_unused_pacas
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/kernel/ima_kexec.c:ima_free_kexec_buffer
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c0000000003f0940-c0000000003f09f8: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe0000486ea)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_dfl_fc_free
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/cma.c:cma_declare_contiguous
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffffffe0000486ea-ffffffe000048748: memblock_free (STB_GLOBAL)
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
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d399)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81a6d399-ffffffff81a6d412: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a298e0)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81a298e0-ffffffff81a29959: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad97a9)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81ad97a9-ffffffff81ad9822: memblock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5c5f)
Location: mm/memblock.c:816
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/mm/numa.c:numa_reset_distance
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_buffer_free
  - mm/memory_hotplug.c:try_remove_memory
  - mm/cma.c:cma_declare_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff81ae5c5f-ffffffff81ae5cd8: memblock_free (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t base</code>
</li>
<li>
<b>Param type changed. </b>
<code>phys_addr_t size</code> ➡️ <code>size_t size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
