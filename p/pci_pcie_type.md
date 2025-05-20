# Function: <code>pci_pcie_type</code>

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
In drivers/pci/access.c (ffffffff8142e297)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81430eb5)
Location: include/linux/pci.h:1820
Inline: True
Inline callers:
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81437be0)
Location: include/linux/pci.h:1820
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/portdrv_bus.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:1820
Inline: True
```
```
In drivers/pci/iov.c (ffffffff81456c07)
Location: include/linux/pci.h:1820
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff81539a3d)
Location: include/linux/pci.h:1820
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
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
In drivers/pci/access.c (ffffffff81479867)
Location: include/linux/pci.h:1894
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8147bb94)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81483800)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/search.c (ffffffff81486d91)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/quirks.c (ffffffff814912f5)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/aspm.c (ffffffff81493d75)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81494ea5)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814951c5)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_resume_noirq
```
```
In drivers/pci/pcie/portdrv_bus.c (ffffffff814956b4)
Location: include/linux/pci.h:1894
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81496a34)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff81497235)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:set_device_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff8149769d)
Location: include/linux/pci.h:1894
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81497d17)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/iov.c (ffffffff814a3ae7)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158e4fd)
Location: include/linux/pci.h:1894
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
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
In drivers/pci/access.c (ffffffff8149acf7)
Location: include/linux/pci.h:1956
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8149d0a4)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff814a4f60)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/search.c (ffffffff814a8541)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/quirks.c (ffffffff814b2b65)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/aspm.c (ffffffff814b5705)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814b6855)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6b75)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_resume_noirq
```
```
In drivers/pci/pcie/portdrv_bus.c (ffffffff814b7074)
Location: include/linux/pci.h:1956
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b83cc)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8b95)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:set_device_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814b8ffd)
Location: include/linux/pci.h:1956
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff814b94ed)
Location: include/linux/pci.h:1956
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff814ba003)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff814c5756)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bc01d)
Location: include/linux/pci.h:1956
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
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
In drivers/pci/access.c (ffffffff814a4a87)
Location: include/linux/pci.h:1988
Inline: True
```
```
In drivers/pci/probe.c (ffffffff814a6fa4)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff814aefb0)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/search.c (ffffffff814b24ad)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/quirks.c (ffffffff814bd109)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/aspm.c (ffffffff814bfdfd)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814c10bd)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c14a5)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_resume_noirq
```
```
In drivers/pci/pcie/portdrv_bus.c (ffffffff814c19b9)
Location: include/linux/pci.h:1988
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2c4c)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814c33c5)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:set_device_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814c37fd)
Location: include/linux/pci.h:1988
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3cdd)
Location: include/linux/pci.h:1988
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff814c4881)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff814cf864)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d1c59)
Location: include/linux/pci.h:1988
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
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
In drivers/pci/access.c (ffffffff814e3861)
Location: include/linux/pci.h:2044
Inline: True
```
```
In drivers/pci/probe.c (ffffffff814e58f4)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff814ee380)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/search.c (ffffffff814f1b9f)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/quirks.c (ffffffff814facd5)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/aspm.c (ffffffff8150017d)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815014ed)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81501975)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_port_resume_noirq
```
```
In drivers/pci/pcie/portdrv_bus.c (ffffffff81501bc9)
Location: include/linux/pci.h:2044
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502e9c)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff81503605)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:set_device_error_reporting
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff81503a3d)
Location: include/linux/pci.h:2044
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81503f1d)
Location: include/linux/pci.h:2044
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff81504dd1)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff8150fa84)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff81638a39)
Location: include/linux/pci.h:2044
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
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
In drivers/pci/access.c (ffffffff81513248)
Location: include/linux/pci.h:2047
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81514d7e)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff81519aa4)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff815204fc)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81521e2f)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/quirks.c (ffffffff8152b9f5)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815304ff)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530af8)
Location: include/linux/pci.h:2047
Inline: True
```
```
In drivers/pci/pcie/aspm.c (ffffffff81531d5d)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff81533945)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff81534d8d)
Location: include/linux/pci.h:2047
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff81535d11)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff81544ac4)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff81673d0d)
Location: include/linux/pci.h:2047
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
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
In drivers/pci/access.c (ffffffff8152893c)
Location: include/linux/pci.h:2094
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8152a49e)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff8152f564)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff8153632c)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81537c5f)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-acpi.c (ffffffff81541b87)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
```
In drivers/pci/quirks.c (ffffffff81542825)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815479bf)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81548088)
Location: include/linux/pci.h:2094
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff81548449)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8154933d)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff8154adf5)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c42d)
Location: include/linux/pci.h:2094
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff8154d3f1)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff8155be91)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169229d)
Location: include/linux/pci.h:2094
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
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
In drivers/pci/access.c (ffffffff81557bd3)
Location: include/linux/pci.h:2168
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81559bc8)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff8155ecc6)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff81565c3d)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff815675ff)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-acpi.c (ffffffff81571229)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
```
In drivers/pci/quirks.c (ffffffff81572135)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81577aaf)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157810f)
Location: include/linux/pci.h:2168
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff81578508)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff815794bd)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff8157acc5)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c11f)
Location: include/linux/pci.h:2168
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff8157d161)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff8158c166)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ca23e)
Location: include/linux/pci.h:2168
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_def_domain_type
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
In drivers/pci/access.c (ffffffff815791ff)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8157ac38)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff81584bd4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff81586f9c)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8158894f)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff815900b3)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pci-acpi.c (ffffffff815925d9)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81593785)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8159922f)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8159989f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff81599c88)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8159ac7d)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff8159c705)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff8159db7f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff8159ebc1)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff815add19)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ed20e)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_def_domain_type
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/pci.h:2142
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e440)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff816202f8)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff8162b80f)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_bridge_d3_update
```
```
In drivers/pci/pci-driver.c (ffffffff8162d8ca)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8162f8ca)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff81637939)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81638b64)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8163907f)
Location: include/linux/pci.h:2160
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff81639449)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff81639f2d)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:alloc_pcie_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff8163c2d0)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d80f)
Location: include/linux/pci.h:2160
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff8163e941)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81640b46)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81641cf5)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/iov.c (ffffffff816564d5)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a52ae)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9591)
Location: include/linux/pci.h:2160
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/pci/access.c (ffffffff81644c5c)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff81646988)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff8165150c)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff81652fba)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81654f5a)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff8165c2f9)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f674)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fb35)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/err.c (ffffffff8165ff66)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/rcec.c (ffffffff81660521)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff81660ddd)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:alloc_pcie_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff81662c40)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/pme.c (ffffffff816644b4)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/pcie/ptm.c (ffffffff81664c84)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81666fb6)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff816680d5)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/iov.c (ffffffff81676a75)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b2700)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b84c1)
Location: include/linux/pci.h:2164
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/pci/access.c (ffffffff816278fc)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff816296a8)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff81633f8c)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff81635a52)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81637ada)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff8163e8ab)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81641c5e)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81642015)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/err.c (ffffffff8164245d)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/rcec.c (ffffffff81642a01)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff816431ab)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff816450b1)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/pme.c (ffffffff81646929)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/pcie/ptm.c (ffffffff81647235)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff816493e9)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8164a5a5)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/iov.c (ffffffff81659095)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff817955f0)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189b8a2)
Location: include/linux/pci.h:2203
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/pci/access.c (ffffffff816971fc)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff816990b5)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff816a416c)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff816a5c42)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff816a7d6a)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff816af43b)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff816b28ea)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2ce5)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/err.c (ffffffff816b3140)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b3701)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff816b3efb)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff816b6061)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/pme.c (ffffffff816b81c9)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/pcie/ptm.c (ffffffff816b8b15)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff816baf49)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff816bc1a5)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/iov.c (ffffffff816cb126)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d460)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192f9a5)
Location: include/linux/pci.h:2264
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/pci/access.c (ffffffff817b899a)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff817ba576)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff817c655c)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff817c8fa0)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff817ca85b)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff817d2901)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff817d6256)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d6705)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/rcec.c (ffffffff817d6b73)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff817d6f58)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff817d9cb1)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/err.c (ffffffff817dbb12)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc5f9)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
```
```
In drivers/pci/pcie/ptm.c (ffffffff817dd00c)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff817e0554)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff817e22b3)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/iov.c (ffffffff817f173e)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff819582d0)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
```
```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a86365)
Location: include/linux/pci.h:2296
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/pci/access.c (ffffffff818d340a)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_cap_has_lnkctl2
```
```
In drivers/pci/probe.c (ffffffff818d551a)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff818e3923)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
```
In drivers/pci/pci-driver.c (ffffffff818e68c0)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff818e835b)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff818f31b1)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7915)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/rcec.c (ffffffff818f8153)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff818faa5f)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb5f1)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/err.c (ffffffff818fd912)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe3a9)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
```
```
In drivers/pci/pcie/ptm.c (ffffffff818ff943)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff81903514)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81905e83)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs_match
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8191737f)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/iov.c (ffffffff81919c69)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/p2pdma.c (ffffffff8191ba88)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:__host_bridge_whitelist
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf390)
Location: include/linux/pci.h:2335
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
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
In drivers/pci/access.c (ffffffff8191646a)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_cap_has_lnkctl2
```
```
In drivers/pci/probe.c (ffffffff8191877a)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff81926ecb)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
```
In drivers/pci/pci-driver.c (ffffffff81929ef2)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8192b96b)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff819365cd)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193ad85)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/rcec.c (ffffffff8193b5b3)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff8193defb)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff8193eaf1)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/err.c (ffffffff81940dc2)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/pme.c (ffffffff81941859)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
```
```
In drivers/pci/pcie/ptm.c (ffffffff81942e86)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff81946bb4)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff819494c3)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs_match
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:pcie_failed_link_retrain
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a98a)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/iov.c (ffffffff8195d289)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/p2pdma.c (ffffffff8195f098)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:__host_bridge_whitelist
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0bd80)
Location: include/linux/pci.h:2427
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
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
In drivers/pci/access.c (ffffffff8195e49a)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_capability_reg_implemented
  - drivers/pci/access.c:pcie_cap_has_lnkctl2
```
```
In drivers/pci/probe.c (ffffffff81960cda)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_alloc_child_bus
```
```
In drivers/pci/pci.c (ffffffff8196f66b)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
```
In drivers/pci/pci-driver.c (ffffffff81972dfa)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff819742bb)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff8197f42d)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983be5)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/rcec.c (ffffffff81984443)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/aspm.c (ffffffff81984888)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff81987ba1)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_aer_raw_clear_status
```
```
In drivers/pci/pcie/err.c (ffffffff8198a022)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/pme.c (ffffffff8198aab9)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
```
```
In drivers/pci/pcie/ptm.c (ffffffff8198c156)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff8198fee0)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81992873)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_rciep_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs_match
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:pcie_failed_link_retrain
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3f88)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/iov.c (ffffffff819a68dd)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/p2pdma.c (ffffffff819a86f8)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:__host_bridge_whitelist
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b60360)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
```
```
In arch/x86/pci/fixup.c (ffffffff82170c77)
Location: include/linux/pci.h:2498
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:amd_rp_pme_resume
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106da668)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffff8000106dd740)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffff8000106e9234)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffff8000106eafb4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffff8000106ecf14)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffff8000106f5234)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pci-acpi.c (ffff8000106f83dc)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffff8000106fa6a0)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/pcie/portdrv_core.c (ffff8000107008d4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff800010700fe8)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffff800010701548)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffff800010702648)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffff8000107043b4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffff800010705b64)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffff800010706f68)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffff800010717c30)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/access.c (c0877d94)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (c087924c)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (c08841e0)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (c088666c)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (c08881d0)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (c088fcb4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (c0892b64)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/pcie/portdrv_core.c (c0898684)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898d94)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (c08991a0)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (c089a0f4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (c089b37c)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (c089cebc)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (c089dea8)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (c08a2368)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d7a30)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_setup_bridge
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_window_alignment
```
```
In drivers/pci/access.c (c000000000852db0)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (c000000000855a08)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (c000000000864090)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (c0000000008664e0)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (c000000000868eb4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (c000000000873d2c)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (c000000000878008)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/iov.c (c000000000887488)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/pci.h:2142
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3ea4)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffffffe0004b59d4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffe0004bf61c)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffe0004c0ff6)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/search.c (ffffffe0004c1d0e)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffe0004c816a)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffe0004ca7ca)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf82a)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfdf8)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffe0004d01be)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffe0004d06c4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d23b0)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3a52)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffe0004d4b2a)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffe0004e0e40)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
</details>
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
In drivers/pci/access.c (ffffffff8156d71f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8156f158)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff815790f4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff8157ba26)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/search.c (ffffffff8157c7df)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff81583f33)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pci-acpi.c (ffffffff81586469)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81587615)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d0bf)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d72f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff8158db18)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158eb0d)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff8158fdb5)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff8159137f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff815923d1)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff815a14e6)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b297e)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_def_domain_type
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
In drivers/pci/access.c (ffffffff8155be8f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8155d8b8)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff81567834)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff81569bfc)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8156b5af)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff81572d13)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pci-acpi.c (ffffffff81575239)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff815763c5)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157bbff)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c26f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff8157c658)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8157d64d)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff8157f0d5)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff8158054f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff81581561)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff81590679)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169063e)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_def_domain_type
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/pci.h:2142
Inline: True
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
In drivers/pci/access.c (ffffffff8156cf4f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8156e988)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff81578924)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff8157acec)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8157c69f)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff81583e03)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pci-acpi.c (ffffffff81586329)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff815874d5)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cf7f)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d5ef)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff8158d9d8)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158e9cd)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff81590455)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff815918cf)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff81592911)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff815a1a69)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e0ece)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_def_domain_type
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/pci.h:2142
Inline: True
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
In drivers/pci/access.c (ffffffff81587a4f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81588e68)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffff81592de4)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (ffffffff815952fc)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81596b4f)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/vc.c (ffffffff8159e2b3)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/pci-acpi.c (ffffffff815a07d9)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff815a1985)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_fsl_no_msi
  - drivers/pci/quirks.c:pci_quirk_al_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a742f)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7a9f)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff815a7e88)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff815a8e7d)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_update_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffff815aa905)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:set_device_error_reporting
  - drivers/pci/pcie/aer.c:aer_get_device_error_info
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffff815abebf)
Location: include/linux/pci.h:2142
Inline: True
```
```
In drivers/pci/pcie/ptm.c (ffffffff815acd91)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (ffffffff815bbe69)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fb4b5)
Location: include/linux/pci.h:2142
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_def_domain_type
```
```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: include/linux/pci.h:2142
Inline: True
```
</details>
</li>
</ul>

## Differences
