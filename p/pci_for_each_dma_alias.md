# Function: <code>pci_for_each_dma_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143ae10)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8143ae10-ffffffff8143af0f: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486d30)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81486d30-ffffffff81486e67: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a84e0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff814a84e0-ffffffff814a8617: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b2440)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff814b2440-ffffffff814b25a2: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f1b30)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff814f1b30-ffffffff814f1c9c: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521dc0)
Location: drivers/pci/search.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81521dc0-ffffffff81521f06: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537bf0)
Location: drivers/pci/search.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81537bf0-ffffffff81537d36: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81567590)
Location: drivers/pci/search.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81567590-ffffffff815676d6: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815888e0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff815888e0-ffffffff81588a25: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f850)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
**Symbols:**

```
ffffffff8162f850-ffffffff8162f9a0: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654ee0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff81654ee0-ffffffff81655030: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81637a60)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff81637a60-ffffffff81637bb8: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a7cf0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/acpi/viot.c:viot_iommu_configure
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816a7cf0-ffffffff816a7e4c: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca7e0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/acpi/viot.c:viot_iommu_configure
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff817ca7e0-ffffffff817ca943: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e82e0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/acpi/viot.c:viot_iommu_configure
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff818e82e0-ffffffff818e8431: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b8f0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/acpi/viot.c:viot_iommu_configure
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8192b8f0-ffffffff8192ba41: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81974240)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/acpi/viot.c:viot_iommu_configure
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff81974240-ffffffff81974391: pci_for_each_dma_alias (STB_GLOBAL)
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
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106eceb0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/acpi/arm64/iort.c:iort_iommu_configure
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
```
**Symbols:**

```
ffff8000106eceb0-ffff8000106ed038: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0888170)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
**Symbols:**

```
c0888170-c0888304: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868e00)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
**Symbols:**

```
c000000000868e00-c00000000086906c: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1cbc)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
```
**Symbols:**

```
ffffffe0004c1cbc-ffffffe0004c1df0: pci_for_each_dma_alias (STB_GLOBAL)
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
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c770)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8157c770-ffffffff8157c8b5: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b540)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8156b540-ffffffff8156b685: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c630)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8157c630-ffffffff8157c775: pci_for_each_dma_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_for_each_dma_alias(struct pci_dev *pdev, int (*fn)(struct pci_dev *, u16, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596ae0)
Location: drivers/pci/search.c:28
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81596ae0-ffffffff81596c25: pci_for_each_dma_alias (STB_GLOBAL)
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
