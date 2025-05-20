# Function: <code>ioremap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bd60)
Location: arch/x86/mm/ioremap.c:313
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
Direct callers:
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - kernel/memremap.c:memremap
  - kernel/memremap.c:memremap
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
```
**Symbols:**

```
ffffffff8106bd60-ffffffff8106bd76: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bdb8)
Location: arch/x86/mm/ioremap.c:312
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - kernel/memremap.c:memremap
  - kernel/memremap.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8106bc10-ffffffff8106bc26: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f9d8)
Location: arch/x86/mm/ioremap.c:312
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - kernel/memremap.c:memremap
  - kernel/memremap.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8106f830-ffffffff8106f846: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f0f8)
Location: arch/x86/mm/ioremap.c:313
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:get_setup_data_paddr
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - kernel/memremap.c:memremap
  - kernel/memremap.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/sfi/sfi_core.c:sfi_map_memory
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8106ef60-ffffffff8106ef76: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81074050)
Location: arch/x86/mm/ioremap.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - kernel/memremap.c:memremap
  - kernel/memremap.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81074050-ffffffff81074066: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81076a60)
Location: arch/x86/mm/ioremap.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81076a60-ffffffff81076a76: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d0f0)
Location: arch/x86/mm/ioremap.c:373
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8107d0f0-ffffffff8107d109: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080840)
Location: arch/x86/mm/ioremap.c:393
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81080840-ffffffff81080859: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081a40)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81081a40-ffffffff81081a59: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810889f0)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:pcc_parse_subspace_irq
```
**Symbols:**

```
ffffffff810889f0-ffffffff81088a09: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088c30)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:pcc_parse_subspace_irq
```
**Symbols:**

```
ffffffff81088c30-ffffffff81088c49: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810898d0)
Location: arch/x86/mm/ioremap.c:417
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff810898d0-ffffffff810898e9: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81098d70)
Location: arch/x86/mm/ioremap.c:417
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81098d70-ffffffff81098d89: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810abb80)
Location: arch/x86/mm/ioremap.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
**Symbols:**

```
ffffffff810abb80-ffffffff810abba8: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c55d0)
Location: arch/x86/mm/ioremap.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
**Symbols:**

```
ffffffff810c55d0-ffffffff810c55f8: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c8d60)
Location: arch/x86/mm/ioremap.c:434
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
**Symbols:**

```
ffffffff810c8d60-ffffffff810c8d88: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d1460)
Location: arch/x86/mm/ioremap.c:434
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
**Symbols:**

```
ffffffff810d1460-ffffffff810d1488: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *ioremap_cache(phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/ioremap.c (ffff8000100adf58)
Location: arch/arm64/mm/ioremap.c:85
Inline: True
Direct callers:
  - arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_prepare
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/firmware/dmi_scan.c:dmi_walk
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/meson/meson_sm.c:meson_sm_map_shmem
```
**Symbols:**

```
ffff8000100adf58-ffff8000100ae060: ioremap_cache (STB_GLOBAL)
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
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t offset, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffe0001d35ba)
Location: kernel/iomem.c:9
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffe0001d35ba-ffffffe0001d35ec: ioremap_cache (STB_WEAK)
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
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080a40)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81080a40-ffffffff81080a59: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f990)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8106f990-ffffffff8106f9a9: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810809f0)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff810809f0-ffffffff81080a09: ioremap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ioremap_cache(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082b10)
Location: arch/x86/mm/ioremap.c:415
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/nvs.c:suspend_nvs_save
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81082b10-ffffffff81082b29: ioremap_cache (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>resource_size_t phys_addr</code> ➡️ <code>phys_addr_t phys_addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
</ul>
</details>
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
