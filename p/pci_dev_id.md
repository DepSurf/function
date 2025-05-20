# Function: <code>pci_dev_id</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81567613)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff8158a8e3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bf675)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c6af6)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf760)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff81588963)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff815ac263)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e2a05)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:setup_aliases
  - drivers/iommu/amd_iommu.c:clone_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e9ab6)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f35a0)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff8162f8de)
Location: include/linux/pci.h:635
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff816552a5)
Location: include/linux/pci.h:635
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd/iommu.c (ffffffff81797ab3)
Location: include/linux/pci.h:635
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:get_devid
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a07ad)
Location: include/linux/pci.h:635
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab2ea)
Location: include/linux/pci.h:635
Inline: True
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
In drivers/pci/search.c (ffffffff81654f6e)
Location: include/linux/pci.h:651
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff8165d48d)
Location: include/linux/pci.h:651
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a707e)
Location: include/linux/pci.h:651
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ad24d)
Location: include/linux/pci.h:651
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b770a)
Location: include/linux/pci.h:651
Inline: True
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
In drivers/pci/search.c (ffffffff81637aee)
Location: include/linux/pci.h:649
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff8163f8e1)
Location: include/linux/pci.h:649
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/iommu/amd/iommu.c (ffffffff81788b0f)
Location: include/linux/pci.h:649
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
```
```
In drivers/iommu/intel/iommu.c (ffffffff8178fd2b)
Location: include/linux/pci.h:649
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179aacb)
Location: include/linux/pci.h:649
Inline: True
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
In drivers/pci/search.c (ffffffff816a7d82)
Location: include/linux/pci.h:665
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff816b0951)
Location: include/linux/pci.h:665
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_set_desc
```
```
In drivers/iommu/amd/iommu.c (ffffffff8181044f)
Location: include/linux/pci.h:665
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181773b)
Location: include/linux/pci.h:665
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818234e4)
Location: include/linux/pci.h:665
Inline: True
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
In drivers/pci/search.c (ffffffff817ca873)
Location: include/linux/pci.h:678
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi/irqdomain.c (ffffffff817d5625)
Location: include/linux/pci.h:678
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/iommu/amd/iommu.c (ffffffff81950910)
Location: include/linux/pci.h:678
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
```
```
In drivers/iommu/intel/iommu.c (ffffffff81958569)
Location: include/linux/pci.h:678
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81963c86)
Location: include/linux/pci.h:678
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff818e8373)
Location: include/linux/pci.h:682
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6645)
Location: include/linux/pci.h:682
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5f80)
Location: include/linux/pci.h:682
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf60f)
Location: include/linux/pci.h:682
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acce1a)
Location: include/linux/pci.h:682
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff8192b983)
Location: include/linux/pci.h:687
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81939aa5)
Location: include/linux/pci.h:687
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b02453)
Location: include/linux/pci.h:687
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b11227)
Location: include/linux/pci.h:687
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19974)
Location: include/linux/pci.h:687
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff819742d3)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982905)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_get_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc
```
```
In drivers/pci/pcie/aer.c (ffffffff819877f9)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/pci/iov.c (ffffffff819a5c59)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_vf_id
  - drivers/pci/iov.c:pci_iov_vf_id
```
```
In drivers/pci/p2pdma.c (ffffffff819aa11a)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b55e6e)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:clone_alias
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b638eb)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6f23a)
Location: include/linux/pci.h:685
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffff8000106ecf84)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffff800010715da4)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_set_desc
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
In drivers/pci/search.c (c088821c)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (c08a06f0)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_set_desc
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
In arch/powerpc/platforms/powernv/npu-dma.c (c0000000000da44c)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu2_unmap_lpar_dev
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu2_unmap_lpar_dev
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu2_map_lpar_dev
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu2_map_lpar_dev
```
```
In drivers/pci/search.c (c000000000868ecc)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
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
In drivers/pci/search.c (ffffffe0004c1d66)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffe0004df452)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_set_desc
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
In drivers/pci/search.c (ffffffff8157c7f3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff8159fa33)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a8455)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:setup_aliases
  - drivers/iommu/amd_iommu.c:clone_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff816af596)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8d90)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff8156b5c3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff8158ebc3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685e45)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:setup_aliases
  - drivers/iommu/amd_iommu.c:clone_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168cee6)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816969d0)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff8157c6b3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff8159ffb3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d66c5)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:setup_aliases
  - drivers/iommu/amd_iommu.c:clone_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dd776)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e7260)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/pci/search.c (ffffffff81596b63)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/msi.c (ffffffff815ba3e3)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_get_device_domain
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
  - drivers/pci/msi.c:pci_msi_domain_calc_hwirq
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f0c75)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:setup_aliases
  - drivers/iommu/amd_iommu.c:clone_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f7b16)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701960)
Location: include/linux/pci.h:608
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
</details>
</li>
</ul>

## Differences
