# Function: <code>pci_find_ext_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435ca0)
Location: drivers/pci/pci.c:343
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81435ca0-ffffffff81435cc3: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481833)
Location: drivers/pci/pci.c:364
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:get_device_error_info
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff814817e0-ffffffff81481803: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2d03)
Location: drivers/pci/pci.c:364
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_aer_init
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff814a2cb0-ffffffff814a2cd3: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aefec)
Location: drivers/pci/pci.c:366
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_aer_init
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff814acb70-ffffffff814acb93: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ebec5)
Location: drivers/pci/pci.c:367
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_aer_init
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff814ebe70-ffffffff814ebe93: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b9f5)
Location: drivers/pci/pci.c:379
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8151b800-ffffffff8151b823: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531685)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81531580-ffffffff815315a3: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155fe55)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8155fdf0-ffffffff8155fe04: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff8155fe10-ffffffff8155fe2f: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580f85)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81580f20-ffffffff81580f34: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff81580f40-ffffffff81580f5f: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626895)
Location: drivers/pci/pci.c:577
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81625f20-ffffffff81625f34: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff816266f0-ffffffff81626713: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164c415)
Location: drivers/pci/pci.c:585
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8164c320-ffffffff8164c343: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162eff5)
Location: drivers/pci/pci.c:585
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8162ef00-ffffffff8162ef23: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169e925)
Location: drivers/pci/pci.c:595
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8169e7f0-ffffffff8169e813: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817be3ed)
Location: drivers/pci/pci.c:612
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aspm.c:pci_restore_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pci_save_aspm_l1ss_state
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff817be160-ffffffff817be17e: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818da70d)
Location: drivers/pci/pci.c:596
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr
  - drivers/pci/quirks.c:dpc_log_size
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff818da440-ffffffff818da45e: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191da4d)
Location: drivers/pci/pci.c:611
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:dpc_log_size
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8191d780-ffffffff8191d79e: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81965e7d)
Location: drivers/pci/pci.c:611
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_enable
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/rcec.c:pci_rcec_init
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:pci_dpc_init
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:dpc_log_size
  - drivers/pci/ats.c:pci_pasid_init
  - drivers/pci/ats.c:pci_pri_init
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff81965bb0-ffffffff81965bce: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3ea8)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffff8000106e3df0-ffff8000106e3e28: pci_find_ext_capability.part.0 (STB_LOCAL)
ffff8000106e3e28-ffff8000106e3e78: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c087fd00)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
c087fc74-c087fc98: pci_find_ext_capability.part.0 (STB_LOCAL)
c087fc98-c087fcc8: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c00000000085e130)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
c00000000085e0c0-c00000000085e0dc: pci_find_ext_capability.part.0 (STB_LOCAL)
c00000000085e0e0-c00000000085e108: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb2ba)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffe0004bb224-ffffffe0004bb258: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffe0004bb258-ffffffe0004bb298: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815754a5)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81575440-ffffffff81575454: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff81575460-ffffffff8157547f: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563c05)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81563ba0-ffffffff81563bb4: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff81563bc0-ffffffff81563bdf: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574cd5)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81574c70-ffffffff81574c84: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff81574c90-ffffffff81574caf: pci_find_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_ext_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f2a5)
Location: drivers/pci/pci.c:545
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/ats.c:pci_max_pasids
  - drivers/pci/ats.c:pci_prg_resp_pasid_required
  - drivers/pci/ats.c:pci_pasid_features
  - drivers/pci/ats.c:pci_disable_pasid
  - drivers/pci/ats.c:pci_enable_pasid
  - drivers/pci/ats.c:pci_reset_pri
  - drivers/pci/ats.c:pci_restore_pri_state
  - drivers/pci/ats.c:pci_disable_pri
  - drivers/pci/ats.c:pci_enable_pri
  - drivers/pci/ats.c:pci_ats_init
  - drivers/pci/iov.c:pci_iov_init
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8158f240-ffffffff8158f254: pci_find_ext_capability.part.0 (STB_LOCAL)
ffffffff8158f260-ffffffff8158f27f: pci_find_ext_capability (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u16</code>
</li>
</ul>
</details>
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
