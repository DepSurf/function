# Function: <code>pci_physfn</code>

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
In drivers/pci/probe.c (ffffffff8142fbc6)
Location: include/linux/pci.h:389
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81433416)
Location: include/linux/pci.h:389
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/ats.c (ffffffff8145588f)
Location: include/linux/pci.h:389
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff815348b6)
Location: include/linux/pci.h:389
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff81539a06)
Location: include/linux/pci.h:389
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
In drivers/pci/probe.c (ffffffff8147b326)
Location: include/linux/pci.h:388
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8148123b)
Location: include/linux/pci.h:388
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/ats.c (ffffffff814a24bf)
Location: include/linux/pci.h:388
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff81589186)
Location: include/linux/pci.h:388
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158e4c6)
Location: include/linux/pci.h:388
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
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
In drivers/pci/probe.c (ffffffff8149c7a6)
Location: include/linux/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff814a4577)
Location: include/linux/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pcie/ptm.c (ffffffff814ba06f)
Location: include/linux/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff814c410f)
Location: include/linux/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff815b6846)
Location: include/linux/pci.h:401
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bbfe6)
Location: include/linux/pci.h:401
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff814a6666)
Location: include/linux/pci.h:424
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff814ae637)
Location: include/linux/pci.h:424
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pcie/ptm.c (ffffffff814c488d)
Location: include/linux/pci.h:424
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff814ce368)
Location: include/linux/pci.h:424
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff815cc686)
Location: include/linux/pci.h:424
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d1c26)
Location: include/linux/pci.h:424
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff814e6b76)
Location: include/linux/pci.h:444
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff814eda07)
Location: include/linux/pci.h:444
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pcie/ptm.c (ffffffff81504ddd)
Location: include/linux/pci.h:444
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff8150e607)
Location: include/linux/pci.h:444
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff81633456)
Location: include/linux/pci.h:444
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff81638a06)
Location: include/linux/pci.h:444
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff815160db)
Location: include/linux/pci.h:443
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff815196ba)
Location: include/linux/pci.h:443
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pcie/ptm.c (ffffffff81535d1d)
Location: include/linux/pci.h:443
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff81543507)
Location: include/linux/pci.h:443
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff8166e635)
Location: include/linux/pci.h:443
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff81673cd5)
Location: include/linux/pci.h:443
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff8152b8bb)
Location: include/linux/pci.h:464
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8152f11a)
Location: include/linux/pci.h:464
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/ptm.c (ffffffff8154d3fd)
Location: include/linux/pci.h:464
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff8155a887)
Location: include/linux/pci.h:464
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff8168ca65)
Location: include/linux/pci.h:464
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff81692265)
Location: include/linux/pci.h:464
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff8155a61b)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8155e87e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffff815787c5)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
```
```
In drivers/pci/pcie/ptm.c (ffffffff8157d16d)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff8158aa2e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff816c44b5)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ca215)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff8157b6ab)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8157f9de)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffff81599f3f)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffffffff8159ebcd)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff815ac35e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff816e7405)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ed1e5)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff81620881)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81625098)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/pcie/aspm.c (ffffffff8163b18f)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
```
```
In drivers/pci/pcie/ptm.c (ffffffff8163e94d)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81640318)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81643ea5)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff81655835)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179dc65)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5285)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2b55)
Location: include/linux/pci.h:498
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
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
In drivers/pci/probe.c (ffffffff81646ea1)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8164acd1)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/pcie/err.c (ffffffff8165ff8d)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff816619df)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
```
```
In drivers/pci/pcie/ptm.c (ffffffff81664c90)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff8166672a)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8166a435)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff81675dd5)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab9a5)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b26d5)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b18a5)
Location: include/linux/pci.h:513
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
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
In drivers/pci/probe.c (ffffffff8162a84d)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8162d885)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/pcie/err.c (ffffffff8164247a)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff816435cf)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
```
```
In drivers/pci/pcie/aer.c (ffffffff816452a5)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/ptm.c (ffffffff81647241)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81648bda)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8164e3a4)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff81658305)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff816589f8)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_vf_msix_count_store
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e805)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff817955c5)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895405)
Location: include/linux/pci.h:512
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
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
In drivers/pci/probe.c (ffffffff81699d2d)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8169cf55)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/pcie/err.c (ffffffff816b315d)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/aspm.c (ffffffff816b4329)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
```
```
In drivers/pci/pcie/aer.c (ffffffff816b613a)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/ptm.c (ffffffff816b8b23)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba5f9)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff816be1c5)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff816ca335)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff816ca938)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_vf_msix_count_store
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816095)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d435)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928e25)
Location: include/linux/pci.h:517
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_core.c:get_pf_vdev
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
In drivers/pci/probe.c (ffffffff817bb364)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff817bef30)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/pcie/aspm.c (ffffffff817d7889)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff817d9d90)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/err.c (ffffffff817dbb30)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/ptm.c (ffffffff817dd07d)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff817dfeb8)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff817e57b1)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff817f06db)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff817f0e68)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:pci_iov_vf_id
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956f55)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff81958195)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a80e34)
Location: include/linux/pci.h:529
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
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
In drivers/pci/probe.c (ffffffff818d6d74)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff818dc3ea)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/setup-res.c (ffffffff818ed162)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/pcie/aspm.c (ffffffff818f8ea9)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb7cf)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/err.c (ffffffff818fd930)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/ptm.c (ffffffff818ff4a5)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff81902de8)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8190a671)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff8191887b)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff81919258)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:pci_iov_vf_id
```
```
In drivers/pci/p2pdma.c (ffffffff8191c912)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abde45)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf255)
Location: include/linux/pci.h:532
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff81919ff4)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8191f71a)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/setup-res.c (ffffffff81930642)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/pcie/aspm.c (ffffffff8193c239)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff8193ed28)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/err.c (ffffffff81940de0)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/ptm.c (ffffffff81942a15)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff81946478)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81949517)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff8195be9b)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff8195c878)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:pci_iov_vf_id
```
```
In drivers/pci/p2pdma.c (ffffffff8195fed2)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a7d5)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b11213)
Location: include/linux/pci.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff819623f4)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8196788a)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_dev_str_match_path
```
```
In drivers/pci/setup-res.c (ffffffff81979016)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/pcie/aspm.c (ffffffff819860a9)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff81987dee)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/err.c (ffffffff8198a040)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/pcie/ptm.c (ffffffff8198bce5)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
  - drivers/pci/pcie/ptm.c:pci_upstream_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff8198f7a8)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff819928c7)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_pericom_acs_store_forward
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/ats.c (ffffffff819a54bb)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pri_supported
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/pci/iov.c (ffffffff819a5e98)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:pci_iov_vf_id
```
```
In drivers/pci/p2pdma.c (ffffffff819a95b7)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e825)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b638d7)
Location: include/linux/pci.h:534
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff82170c85)
Location: include/linux/pci.h:534
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
In drivers/pci/probe.c (ffff8000106deb1c)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffff8000106e2500)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffff800010701820)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffff800010706f74)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffff800010716654)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
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
In drivers/pci/probe.c (c087a7f8)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (c087e178)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (c0899450)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (c089df1c)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (c08a0778)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
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
In drivers/pci/probe.c (c0000000008577c4)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (c00000000085bd48)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/ats.c (c000000000885da0)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
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
In drivers/pci/probe.c (ffffffe0004b6cb0)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffe0004b9f3e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffe0004d0510)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffffffe0004d4b36)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffe0004df514)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
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
In drivers/pci/probe.c (ffffffff8156fbcb)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff81573efe)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158ddcf)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffffffff815923dd)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff8159fb2e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff816acee5)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b2955)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff8155e32b)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8156265e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffff8157c90f)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffffffff8158156d)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff8158ecbe)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff8168a845)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff81690615)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff8156f3fb)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8157372e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158dc8f)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffffffff8159291d)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff815a00ae)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff816db0c5)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e0ea5)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
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
In drivers/pci/probe.c (ffffffff815898db)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
```
```
In drivers/pci/pci.c (ffffffff8158dc0e)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_find_pcie_root_port
  - drivers/pci/pci.c:pci_dev_str_match
```
```
In drivers/pci/pcie/aspm.c (ffffffff815a813f)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
```
```
In drivers/pci/pcie/ptm.c (ffffffff815acd9d)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/ats.c (ffffffff815ba4de)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/iommu/dmar.c (ffffffff816f5675)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_find_matched_drhd_unit
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fb485)
Location: include/linux/pci.h:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
</details>
</li>
</ul>

## Differences
