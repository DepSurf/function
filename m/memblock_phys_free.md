# Function: <code>memblock_phys_free</code>

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
int memblock_phys_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f207c6)
Location: mm/memblock.c:827
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/mm/init.c:init_mem_mapping
  - mm/memblock.c:memblock_free
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_free_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
**Symbols:**

```
ffffffff81f207c6-ffffffff81f20853: memblock_phys_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memblock_phys_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820ca170)
Location: mm/memblock.c:842
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:ima_free_kexec_buffer
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - mm/memblock.c:memblock_double_array
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff820ca170-ffffffff820ca24d: memblock_phys_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memblock_phys_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214e400)
Location: mm/memblock.c:855
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:ima_free_kexec_buffer
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - mm/memblock.c:memblock_double_array
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8214e400-ffffffff8214e4dd: memblock_phys_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memblock_phys_free(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82231170)
Location: mm/memblock.c:895
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_del_extra_mem
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - kernel/crash_core.c:reserve_crashkernel_generic
  - mm/memblock.c:memblock_double_array
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff82231170-ffffffff8223124d: memblock_phys_free (STB_GLOBAL)
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
