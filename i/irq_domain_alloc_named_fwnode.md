# Function: <code>irq_domain_alloc_named_fwnode</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff820b7088)
Location: include/linux/irqdomain.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b123)
Location: include/linux/irqdomain.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff820b827c)
Location: include/linux/irqdomain.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff826bd9a4)
Location: include/linux/irqdomain.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f633)
Location: include/linux/irqdomain.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff826e7758)
Location: include/linux/irqdomain.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81062743)
Location: include/linux/irqdomain.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff8289e2a1)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81068443)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828b6130)
Location: include/linux/irqdomain.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106bc33)
Location: include/linux/irqdomain.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828b95f3)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c7e3)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109867c)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff82cde5f9)
Location: include/linux/irqdomain.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81073b23)
Location: include/linux/irqdomain.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109de6c)
Location: include/linux/irqdomain.h:240
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff82fca9b7)
Location: include/linux/irqdomain.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074886)
Location: include/linux/irqdomain.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099a3f)
Location: include/linux/irqdomain.h:241
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/iommu/amd/init.c (ffffffff817a9500)
Location: include/linux/irqdomain.h:241
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
```
```
In arch/x86/pci/xen.c (ffffffff83020a77)
Location: include/linux/irqdomain.h:241
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
In arch/x86/hyperv/irqdomain.c (ffffffff831c5167)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d5316)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81075336)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a24c)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/iommu/amd/init.c (ffffffff8178b45c)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
```
In arch/x86/pci/xen.c (ffffffff8322bc45)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
In arch/x86/hyperv/irqdomain.c (ffffffff832a5e21)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b7e48)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81082826)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa276)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/iommu/amd/init.c (ffffffff81812b8d)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
```
In arch/x86/pci/xen.c (ffffffff8331646a)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
In arch/x86/hyperv/irqdomain.c (ffffffff83454f47)
Location: include/linux/irqdomain.h:250
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469b13)
Location: include/linux/irqdomain.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8109241f)
Location: include/linux/irqdomain.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfce0)
Location: include/linux/irqdomain.h:250
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/iommu/amd/init.c (ffffffff81953b4e)
Location: include/linux/irqdomain.h:250
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
```
In arch/x86/pci/xen.c (ffffffff834d0dd9)
Location: include/linux/irqdomain.h:250
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
In arch/x86/hyperv/irqdomain.c (ffffffff83e72b55)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e805)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810a740f)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbbd0)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/msi.c (ffffffff811a51b2)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_create_device_irq_domain
```
```
In drivers/iommu/amd/init.c (ffffffff81ab9236)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
```
In arch/x86/pci/xen.c (ffffffff83f14f35)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
In arch/x86/hyperv/irqdomain.c (ffffffff83693a65)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b20a5)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810aa66f)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e71ad)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/msi.c (ffffffff811b734a)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_create_device_irq_domain
```
```
In drivers/iommu/amd/init.c (ffffffff81b0569f)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
```
In arch/x86/pci/xen.c (ffffffff8373b6b5)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
In arch/x86/hyperv/irqdomain.c (ffffffff838c3605)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e2565)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810b16ef)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef55d)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/msi.c (ffffffff811c720a)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_create_device_irq_domain
```
```
In drivers/iommu/amd/init.c (ffffffff81b58716)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
```
```
In arch/x86/pci/xen.c (ffffffff83970035)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828a75fa)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c2d3)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff8289f6f7)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c5f3)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828ba50a)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c783)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828ba620)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106de83)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099b4c)
Location: include/linux/irqdomain.h:239
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
</details>
</li>
</ul>

## Differences
