# Function: <code>__order_base_2</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81312e86)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/ext4/indirect.c (ffffffff8131f974)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/jbd2/journal.c (ffffffff81332f96)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/log2.h:198
Inline: False
```
```
In drivers/iommu/iova.c (ffffffff815ad6ac)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181efde)
Location: include/linux/log2.h:198
Inline: True
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
In fs/ext4/indirect.c (ffffffff812f8522)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff8130a396)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813485d6)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d22a2)
Location: include/linux/log2.h:198
Inline: True
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:198
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff815c32cc)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fc1f)
Location: include/linux/log2.h:198
Inline: True
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
In fs/ext4/indirect.c (ffffffff8131cb5f)
Location: include/linux/log2.h:189
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff8132ee76)
Location: include/linux/log2.h:189
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff8136cc26)
Location: include/linux/log2.h:189
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d58c0)
Location: include/linux/log2.h:189
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815126d2)
Location: include/linux/log2.h:189
Inline: True
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:189
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81629c4c)
Location: include/linux/log2.h:189
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff818befbf)
Location: include/linux/log2.h:189
Inline: True
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
In fs/ext4/indirect.c (ffffffff8134aab3)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff8135d455)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff8139c815)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pci/pci.c (ffffffff8151bc35)
Location: include/linux/log2.h:202
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81547333)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549288)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff81664945)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914bfe)
Location: include/linux/log2.h:202
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff811f35a4)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff81362c83)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff81375985)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813b40e5)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pci/pci.c (ffffffff81533a65)
Location: include/linux/log2.h:202
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155da21)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155f9b8)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff81682f35)
Location: include/linux/log2.h:202
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff819433b0)
Location: include/linux/log2.h:202
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8120b2a9)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff8138bcb6)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff8139ef45)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813de6f5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158de7a)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815902b5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff816bab85)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7958)
Location: include/linux/log2.h:198
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff81218589)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff813a4706)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff813b7d65)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813f9ca5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815afa9a)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1fe5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff816dd9e5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de9e8)
Location: include/linux/log2.h:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __order_base_2(long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81242e80)
Location: include/linux/log2.h:198
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81402f80)
Location: include/linux/log2.h:198
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff814457a5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
Direct callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81658bf0)
Location: include/linux/log2.h:198
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b388)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff817947f5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
Direct callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179f200)
Location: include/linux/log2.h:198
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:to_vtd_size
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb5c0)
Location: include/linux/log2.h:198
Inline: False
```
**Symbols:**

```
ffffffff81242e80-ffffffff81242e99: __order_base_2 (STB_LOCAL)
ffffffff81402f80-ffffffff81402f99: __order_base_2 (STB_LOCAL)
ffffffff81445780-ffffffff81445791: __order_base_2.part.0 (STB_LOCAL)
ffffffff81658bf0-ffffffff81658c09: __order_base_2 (STB_LOCAL)
ffffffff8165b330-ffffffff8165b341: __order_base_2.part.0 (STB_LOCAL)
ffffffff81793990-ffffffff817939a1: __order_base_2.part.0 (STB_LOCAL)
ffffffff8179f200-ffffffff8179f219: __order_base_2 (STB_LOCAL)
ffffffff81acb5c0-ffffffff81acb5d9: __order_base_2 (STB_LOCAL)
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
In kernel/events/ring_buffer.c (ffffffff8124e77d)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8141cef2)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff81462315)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632cfc)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81679038)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bd28)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b1631)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
```
```
In drivers/iommu/iova.c (ffffffff817c0d80)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad76b6)
Location: include/linux/log2.h:199
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
In kernel/events/ring_buffer.c (ffffffff8125307d)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81423568)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff814679c5)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816169fb)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165b9a8)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ebf8)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179419b)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
```
```
In drivers/iommu/intel/svm.c (ffffffff81798986)
Location: include/linux/log2.h:199
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff817a3fe0)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2761)
Location: include/linux/log2.h:199
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
In kernel/events/ring_buffer.c (ffffffff8128e964)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81476de4)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff814bd905)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81685c6b)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce0d4)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d17b8)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181c004)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
```
```
In drivers/iommu/intel/svm.c (ffffffff81821199)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/iova.c (ffffffff8182d165)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81d022ef)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b805e5)
Location: include/linux/log2.h:199
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
In kernel/rcu/update.c (ffffffff81173b29)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/events/ring_buffer.c (ffffffff812e385a)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/mballoc.c (ffffffff814f90de)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff81549005)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a2508)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6d4d)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa868)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff81961340)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/iova.c (ffffffff8196e705)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81eca889)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d109c0)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
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
In kernel/rcu/update.c (ffffffff811a99dd)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/events/ring_buffer.c (ffffffff8134bf0a)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/vmscan.c (ffffffff8137b672)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/workingset.c (ffffffff813acf9c)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In fs/buffer.c (ffffffff814d394f)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff814d906f)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/ext4/mballoc.c (ffffffff8159383e)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff815e8745)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In block/bdev.c (ffffffff8172a4b1)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b9781)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8192283d)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926f08)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca70f)
Location: include/linux/log2.h:199
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81ad9075)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adba22)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6720)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
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
In kernel/rcu/update.c (ffffffff811bb8ca)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/events/ring_buffer.c (ffffffff8137cf5a)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/vmscan.c (ffffffff813ad906)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/workingset.c (ffffffff813e13b0)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In fs/buffer.c (ffffffff81508a28)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/buffer.c:folio_init_buffers
```
```
In fs/direct-io.c (ffffffff81511f0a)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/ext4/mballoc.c (ffffffff815ca84e)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff816200b5)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In block/bdev.c (ffffffff817667ee)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fc900)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819665e0)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b0d8)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff81b1741f)
Location: include/linux/log2.h:199
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81b27135)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b29ce2)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f356b7)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
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
In kernel/rcu/update.c (ffffffff811cbdb0)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/events/ring_buffer.c (ffffffff813a61ba)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/vmscan.c (ffffffff813d6d19)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/workingset.c (ffffffff8140bc6d)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In fs/buffer.c (ffffffff8153d887)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/buffer.c:folio_init_buffers
```
```
In fs/direct-io.c (ffffffff815463d1)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/ext4/mballoc.c (ffffffff8160365e)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/jbd2/journal.c (ffffffff81659085)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In block/bdev.c (ffffffff817a831e)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - block/bdev.c:sb_min_blocksize
  - block/bdev.c:set_blocksize
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943a45)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819afcf0)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4907)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c95f)
Location: include/linux/log2.h:199
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79e81)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff81b7d745)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/iommu/iova.c:alloc_iova_fast
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b80cd5)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In net/ipv4/tcp_metrics.c (ffffffff839699a3)
Location: include/linux/log2.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
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
In kernel/events/ring_buffer.c (ffff8000102a3000)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffff800010477f20)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffff80001048dffc)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffff8000104d67d0)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ae8b8)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071bd3c)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722e08)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e988)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e92c4)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/sunxi/clk-sunxi.c (ffff8000107f2178)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sunxi.c:sun5i_a13_get_ahb_factors
```
```
In drivers/clk/sunxi/clk-sun9i-core.c (ffff8000107f332c)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_get_apb1_factors
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_get_apb1_factors
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_get_ahb_factors
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_get_ahb_factors
```
```
In drivers/iommu/iova.c (ffff8000108cdee8)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc3dc)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91b7c)
Location: include/linux/log2.h:198
Inline: True
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
In fs/ext4/indirect.c (c06398f0)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (c064ee20)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (c0696fe8)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084e8c0)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pci/endpoint/pci-epc-core.c (c08a4cf8)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/pcie-rcar.c (c08afb38)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7ef4)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad9ccc)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
```
```
In net/ipv4/tcp_metrics.c (c0da0878)
Location: include/linux/log2.h:198
Inline: True
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
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f1640)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
```
```
In kernel/events/ring_buffer.c (c0000000003553c0)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (c00000000059a5cc)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (c0000000005b4c9c)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (c00000000060f4b0)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b6f0)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In net/ipv4/tcp_metrics.c (c000000000da2140)
Location: include/linux/log2.h:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __order_base_2(long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d18ac)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffe000303194)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffe000313c5e)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffe00034c980)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
Direct callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e2738)
Location: include/linux/log2.h:198
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8d32)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1c16)
Location: include/linux/log2.h:198
Inline: True
```
**Symbols:**

```
ffffffe00034c278-ffffffe00034c2ca: __order_base_2.part.0 (STB_LOCAL)
ffffffe0004e2738-ffffffe0004e277c: __order_base_2 (STB_LOCAL)
ffffffe0004e8614-ffffffe0004e8660: __order_base_2.part.0 (STB_LOCAL)
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
In kernel/events/ring_buffer.c (ffffffff81210bd9)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff8139cce6)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff813b0345)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813f2285)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a325a)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a57a5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff816a3435)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e858)
Location: include/linux/log2.h:198
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff81203969)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff8138d776)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff813a0dd5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813e2d05)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815923fa)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594945)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff81680e25)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938318)
Location: include/linux/log2.h:198
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
In kernel/events/ring_buffer.c (ffffffff8120e979)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff8139a546)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff813adba5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff813ef605)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a37ea)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5d35)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff816d16a5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9028)
Location: include/linux/log2.h:198
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
In kernel/events/ring_buffer.c (ffffffff8121d889)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In fs/ext4/indirect.c (ffffffff813aea06)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/mballoc.c (ffffffff813c2565)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/jbd2/journal.c (ffffffff81404fc5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bdbea)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c0135)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/iova.c (ffffffff816eaff5)
Location: include/linux/log2.h:198
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d88)
Location: include/linux/log2.h:198
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
