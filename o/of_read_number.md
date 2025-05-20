# Function: <code>of_read_number</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 of_read_number(const __be32 *cell, int size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff8000114359e4)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_init_cpus
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff8000106812b4)
Location: include/linux/of.h:234
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
```
```
In drivers/iommu/of_iommu.c (ffff8000108cea88)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
```
```
In drivers/firmware/efi/efi.c (ffff8000114a5378)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
```
```
In drivers/of/base.c (0)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
```
In drivers/of/platform.c (0)
Location: include/linux/of.h:234
Inline: True
```
```
In drivers/of/property.c (ffff800010b6fbc0)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_u64
```
```
In drivers/of/fdt.c (ffff800010b72324)
Location: include/linux/of.h:234
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:dt_mem_next_cell
```
```
In drivers/of/fdt_address.c (ffff800010b7242c)
Location: include/linux/of.h:234
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_translate
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
```
```
In drivers/of/address.c (ffff800010b7422c)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_get_pci_address
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
```
```
In drivers/of/of_reserved_mem.c (ffff8000114ac638)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
```
In drivers/of/of_numa.c (ffff800010b78bdc)
Location: include/linux/of.h:234
Inline: True
Direct callers:
  - drivers/of/of_numa.c:of_numa_init
  - drivers/of/of_numa.c:of_numa_init
  - drivers/of/of_numa.c:of_numa_init
```
**Symbols:**

```
ffff8000106812b4-ffff8000106812e4: of_read_number (STB_LOCAL)
ffff800010b72324-ffff800010b72354: of_read_number (STB_LOCAL)
ffff800010b7242c-ffff800010b7245c: of_read_number (STB_LOCAL)
ffff800010b78bdc-ffff800010b78be8: of_read_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/bus/mvebu-mbus.c (c154f50c)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
```
```
In drivers/pci/controller/pci-mvebu.c (c08a95d4)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_get_tgt_attr
  - drivers/pci/controller/pci-mvebu.c:mvebu_get_tgt_attr
  - drivers/pci/controller/pci-mvebu.c:mvebu_get_tgt_attr
```
```
In drivers/iommu/of_iommu.c (c09c1338)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
```
```
In drivers/mtd/parsers/ofpart.c (c0a977f8)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/mtd/parsers/ofpart.c:parse_fixed_partitions
  - drivers/mtd/parsers/ofpart.c:parse_fixed_partitions
```
```
In drivers/firmware/efi/efi.c (c15a79c4)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
```
```
In drivers/of/base.c (c0c4e070)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
```
In drivers/of/platform.c (c0c50988)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/property.c (c0c514a8)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_u64
```
```
In drivers/of/fdt.c (c15aefc8)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:dt_mem_next_cell
```
```
In drivers/of/fdt_address.c (c15b05e4)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_translate
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
```
```
In drivers/of/address.c (c0c5627c)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_get_pci_address
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
```
```
In drivers/of/of_reserved_mem.c (c15b0d48)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/cacheinfo.c (c00000000002a2d0)
Location: include/linux/of.h:234
Inline: True
```
```
In arch/powerpc/kernel/time.c (c000000001348adc)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:get_freq
```
```
In arch/powerpc/kernel/prom.c (c000000001349c50)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
```
In arch/powerpc/kernel/prom_parse.c (c000000000030dbc)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom_parse.c:of_parse_dma_window
  - arch/powerpc/kernel/prom_parse.c:of_parse_dma_window
  - arch/powerpc/kernel/prom_parse.c:of_parse_dma_window
  - arch/powerpc/kernel/prom_parse.c:of_parse_dma_window
  - arch/powerpc/kernel/prom_parse.c:of_parse_dma_window
```
```
In arch/powerpc/kernel/fadump.c (c00000000004d884)
Location: include/linux/of.h:234
Inline: True
```
```
In arch/powerpc/kernel/legacy_serial.c (c000000001351b48)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
```
```
In arch/powerpc/kernel/pci_dn.c (c00000000006a1f4)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_dn.c:pci_traverse_device_nodes
  - arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info
  - arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info
  - arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info
  - arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info
  - arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info
```
```
In arch/powerpc/kernel/isa-bridge.c (c0000000013522d8)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_init_non_pci
```
```
In arch/powerpc/kernel/pci_of_scan.c (c00000000006fa30)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:get_int_prop
```
```
In arch/powerpc/kernel/ima_kexec.c (c0000000000727ac)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/kernel/ima_kexec.c:do_get_kexec_buffer
  - arch/powerpc/kernel/ima_kexec.c:do_get_kexec_buffer
```
```
In arch/powerpc/mm/drmem.c (c0000000013549b8)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/mm/drmem.c:drmem_init
  - arch/powerpc/mm/drmem.c:drmem_init
  - arch/powerpc/mm/drmem.c:__walk_drmem_v2_lmbs
  - arch/powerpc/mm/drmem.c:read_drconf_v2_cell
  - arch/powerpc/mm/drmem.c:read_drconf_v2_cell
  - arch/powerpc/mm/drmem.c:read_drconf_v2_cell
  - arch/powerpc/mm/drmem.c:read_drconf_v2_cell
  - arch/powerpc/mm/drmem.c:__walk_drmem_v1_lmbs
  - arch/powerpc/mm/drmem.c:read_drconf_v1_cell
  - arch/powerpc/mm/drmem.c:read_drconf_v1_cell
  - arch/powerpc/mm/drmem.c:read_drconf_v1_cell
```
```
In arch/powerpc/mm/numa.c (c0000000000a2e58)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:numa_setup_drmem_lmb
  - arch/powerpc/mm/numa.c:numa_setup_drmem_lmb
  - arch/powerpc/mm/numa.c:numa_setup_drmem_lmb
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c00000000135955c)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
```
```
In arch/powerpc/platforms/powernv/opal.c (c00000000135b920)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
```
```
In arch/powerpc/platforms/powernv/opal-fadump.c (c00000000135f574)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c00000000136029c)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000000ee7a8)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs
  - arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs
  - arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs
  - arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size
  - arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size
  - arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size
  - arch/powerpc/platforms/pseries/setup.c:pseries_get_iov_fw_value
  - arch/powerpc/platforms/pseries/setup.c:pseries_get_iov_fw_value
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f14e0)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
```
```
In arch/powerpc/platforms/pseries/pci.c (c0000000000f5260)
Location: include/linux/of.h:234
Inline: True
```
```
In arch/powerpc/platforms/pseries/vio.c (c0000000001013b0)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_find_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
```
In arch/powerpc/platforms/pseries/rtas-fadump.c (c000000001364c24)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan
```
```
In drivers/tty/hvc/hvc_vio.c (0)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_vio.c:hvc_vio_init_early
```
```
In drivers/iommu/of_iommu.c (c0000000009703c4)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
```
```
In drivers/of/base.c (c000000000c44340)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/base.c:__of_find_n_match_cpu_property
```
```
In drivers/of/property.c (c000000000c491a0)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_u64
```
```
In drivers/of/fdt.c (c0000000013ba984)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:dt_mem_next_cell
```
```
In drivers/of/fdt_address.c (c0000000013bc124)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_translate
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
```
```
In drivers/of/address.c (c000000000c50ccc)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_get_pci_address
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
```
```
In drivers/of/of_reserved_mem.c (c0000000013bcb10)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 of_read_number(const __be32 *cell, int size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720200)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
```
In drivers/of/property.c (ffffffe000723f16)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_u64
```
```
In drivers/of/fdt.c (ffffffe000725ff0)
Location: include/linux/of.h:234
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:dt_mem_next_cell
```
```
In drivers/of/fdt_address.c (ffffffe0007260ca)
Location: include/linux/of.h:234
Inline: False
Direct callers:
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_translate
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
  - drivers/of/fdt_address.c:fdt_bus_default_map
```
```
In drivers/of/address.c (ffffffe000727c2a)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_get_pci_address
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
```
```
In drivers/of/of_reserved_mem.c (ffffffe00003c62a)
Location: include/linux/of.h:234
Inline: True
Inline callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffffffe000725ff0-ffffffe000726042: of_read_number (STB_LOCAL)
ffffffe0007260ca-ffffffe00072611c: of_read_number (STB_LOCAL)
```
</details>
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
