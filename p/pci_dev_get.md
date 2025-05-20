# Function: <code>pci_dev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81438e20)
Location: drivers/pci/pci-driver.c:1375
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff81438e20-ffffffff81438e44: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814866fe)
Location: drivers/pci/pci-driver.c:1372
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff81484cf0-ffffffff81484d14: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a7ebe)
Location: drivers/pci/pci-driver.c:1381
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff814a6470-ffffffff814a6494: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b1e6b)
Location: drivers/pci/pci-driver.c:1399
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff814b0410-ffffffff814b0434: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814f154b)
Location: drivers/pci/pci-driver.c:1468
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff814ef950-ffffffff814ef974: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8152174b)
Location: drivers/pci/pci-driver.c:1489
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8151f990-ffffffff8151f9b4: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8153757b)
Location: drivers/pci/pci-driver.c:1486
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff815357a0-ffffffff815357c4: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566ed5)
Location: drivers/pci/pci-driver.c:1520
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff81565150-ffffffff81565176: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81588235)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff81586490-ffffffff815864b6: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162ef61)
Location: drivers/pci/pci-driver.c:1498
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device
  - arch/x86/pci/i386.c:pcibios_save_fw_addr
```
**Symbols:**

```
ffffffff8162cfe0-ffffffff8162d008: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81654621)
Location: drivers/pci/pci-driver.c:1477
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arbiter_del_pci_device
  - arch/x86/pci/i386.c:pcibios_save_fw_addr
```
**Symbols:**

```
ffffffff816526d0-ffffffff816526f8: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81636fe5)
Location: drivers/pci/pci-driver.c:1477
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:pci_notify
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81635190-ffffffff816351b8: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a7234)
Location: drivers/pci/pci-driver.c:1491
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:pci_notify
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff816a5300-ffffffff816a5328: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9c9e)
Location: drivers/pci/pci-driver.c:1520
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff817c7950-ffffffff817c797d: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e76de)
Location: drivers/pci/pci-driver.c:1526
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff818e5080-ffffffff818e50ad: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8192acfe)
Location: drivers/pci/pci-driver.c:1527
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff819286c0-ffffffff819286ed: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8197358e)
Location: drivers/pci/pci-driver.c:1540
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pci/vgaarb.c:pci_notify
  - drivers/pci/vgaarb.c:vga_arb_write
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81970eb0-ffffffff81970edd: pci_dev_get (STB_GLOBAL)
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
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ec640)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
```
**Symbols:**

```
ffff8000106eaad0-ffff8000106eab04: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0887944)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
```
**Symbols:**

```
c08859b0-c08859dc: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0000000008682c0)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
```
**Symbols:**

```
c000000000865d90-c000000000865ddc: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c16c8)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
```
**Symbols:**

```
ffffffe0004c09de-ffffffe0004c0a0e: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157c0c5)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8157a9b0-ffffffff8157a9d6: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156ae95)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff815690f0-ffffffff81569116: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bf85)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8157a1e0-ffffffff8157a206: pci_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_dev_get(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81596435)
Location: drivers/pci/pci-driver.c:1533
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_set_default_device
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff815947f0-ffffffff81594816: pci_dev_get (STB_GLOBAL)
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
