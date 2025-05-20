# Function: <code>read_pci_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff816fa830)
Location: arch/x86/pci/early.c:10
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_device
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:intel_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff816fa830-ffffffff816fa86a: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8175f9a5)
Location: arch/x86/pci/early.c:10
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8175f6b0-ffffffff8175f6ea: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8178bee5)
Location: arch/x86/pci/early.c:10
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8178bbf0-ffffffff8178bc2a: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff817aae76)
Location: arch/x86/pci/early.c:10
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff817aabb0-ffffffff817aabea: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81822366)
Location: arch/x86/pci/early.c:11
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818220a0-ffffffff818220da: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186c584)
Location: arch/x86/pci/early.c:11
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
  - arch/x86/pci/early.c:early_dump_pci_device
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8186c370-ffffffff8186c3ab: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8188c450)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8188c450-ffffffff8188c48b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818d6d90)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818d6d90-ffffffff818d6dcb: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81909110)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff81909110-ffffffff8190914b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bb9a00)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs
  - arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs
```
**Symbols:**

```
ffffffff81bb9a00-ffffffff81bb9a3b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bce300)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:detect_ivrs
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs
  - arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs
```
**Symbols:**

```
ffffffff81bce300-ffffffff81bce33b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bc1cc0)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81bc1cc0-ffffffff81bc1cfb: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81c922d0)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81c922d0-ffffffff81c9230b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81e41950)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81e41950-ffffffff81e41997: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8201bfe0)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8201bfe0-ffffffff8201c027: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8209c680)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8209c680-ffffffff8209c6c7: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff82173e60)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff82173e60-ffffffff82173ea7: read_pci_config (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818a84d0)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818a84d0-ffffffff818a850b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81862ee0)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff81862ee0-ffffffff81862f1b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818f9b30)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818f9b30-ffffffff818f9b6b: read_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 read_pci_config(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8191ac90)
Location: arch/x86/pci/early.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen11_stolen_base
  - arch/x86/kernel/early-quirks.c:gen3_stolen_base
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs_contd
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_bus_has_devices
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8191ac90-ffffffff8191accb: read_pci_config (STB_GLOBAL)
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
