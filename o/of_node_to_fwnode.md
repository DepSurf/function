# Function: <code>of_node_to_fwnode</code>

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
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810565b6)
Location: include/linux/irqdomain.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/htirq.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff810e0c46)
Location: include/linux/irqdomain.h:209
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156c2d3)
Location: include/linux/irqdomain.h:209
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81583591)
Location: include/linux/irqdomain.h:209
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de85)
Location: include/linux/irqdomain.h:209
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:209
Inline: True
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
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056839)
Location: include/linux/irqdomain.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/htirq.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff810e65a6)
Location: include/linux/irqdomain.h:224
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c148c)
Location: include/linux/irqdomain.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/base/platform-msi.c (ffffffff815c2442)
Location: include/linux/irqdomain.h:224
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d96a6)
Location: include/linux/irqdomain.h:224
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2d80)
Location: include/linux/irqdomain.h:224
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:224
Inline: True
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
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810595e9)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/htirq.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff810ecf96)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f08cc)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81606396)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:231
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fc30)
Location: include/linux/irqdomain.h:231
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:231
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81058c51)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff810ec936)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irqdomain.h:263
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816046d6)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:263
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a176)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:263
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623cf0)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:263
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d131)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff810f51a6)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166cab6)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81682846)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c5e0)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:270
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810600f1)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff810fd590)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8154941a)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a8872)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be8c2)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c86b0)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:270
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81065e61)
Location: include/linux/irqdomain.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81109030)
Location: include/linux/irqdomain.h:272
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fb1a)
Location: include/linux/irqdomain.h:272
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c943e)
Location: include/linux/irqdomain.h:272
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:272
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfc92)
Location: include/linux/irqdomain.h:272
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:272
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9bb0)
Location: include/linux/irqdomain.h:272
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:272
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069616)
Location: include/linux/irqdomain.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8111260b)
Location: include/linux/irqdomain.h:274
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8159041a)
Location: include/linux/irqdomain.h:274
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81704783)
Location: include/linux/irqdomain.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:274
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817193a2)
Location: include/linux/irqdomain.h:274
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:274
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81723340)
Location: include/linux/irqdomain.h:274
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:274
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069f96)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8111e89b)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b214a)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81728ad3)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d692)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817475e0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81070c0e)
Location: include/linux/irqdomain.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8112a54b)
Location: include/linux/irqdomain.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165bb0a)
Location: include/linux/irqdomain.h:282
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e5126)
Location: include/linux/irqdomain.h:282
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:282
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817fb044)
Location: include/linux/irqdomain.h:282
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:282
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818052e0)
Location: include/linux/irqdomain.h:282
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:282
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81071fa9)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81127400)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bf17)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d3a4)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815bd0)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:289
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072abd)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff811276c2)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165edd7)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:285
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1b42)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:285
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa290)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:285
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irqdomain.h:285
Inline: True
```
```
In drivers/mfd/tps6586x.c (ffffffff81c06e09)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107e9c6)
Location: include/linux/irqdomain.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81147c32)
Location: include/linux/irqdomain.h:284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1987)
Location: include/linux/irqdomain.h:284
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a794)
Location: include/linux/irqdomain.h:284
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:284
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81883780)
Location: include/linux/irqdomain.h:284
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:284
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irqdomain.h:284
Inline: True
```
```
In drivers/mfd/tps6586x.c (ffffffff81d0a407)
Location: include/linux/irqdomain.h:284
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108e317)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8116c0c8)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817faa67)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c2ec4)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:298
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc270)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:298
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irqdomain.h:298
Inline: True
```
```
In drivers/mfd/tps6586x.c (ffffffff81ed287b)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a2ab7)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff811a09a8)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8192726a)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b39186)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:286
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b4400f)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:286
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irqdomain.h:286
Inline: True
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a60b)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5b5d)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff811b2822)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b43a)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8c5f6)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b973ef)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9da4b)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810acb0d)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff811c2612)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4f1a)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81be04f6)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb3bf)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irqdomain.h:289
Inline: True
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1a3b)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
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
In kernel/irq/irqdomain.c (ffff8000101841dc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/irqchip/irq-al-fic.c (ffff800011470688)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/irqchip/irq-bcm2835.c (ffff800011470870)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/irqchip/irq-bcm2836.c (ffff800011470ab8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470d50)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-sun4i.c (ffff80001147100c)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff800011471178)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472a9c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:partition_domain_translate
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (ffff800011474d2c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (ffff800011474f3c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (ffff8000114750a8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff80001067682c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800011475444)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff80001147561c)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800011475a1c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff800011475bf0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800011475d78)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678d14)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff80001147601c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a14c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a738)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b4dc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff8000114764c0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_dt_init
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff800011476694)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067cea8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d7ac)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/irqchip/irq-ti-sci-intr.c (ffff80001067e084)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e6f0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699b40)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b6900)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7e34)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf388)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d05d0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/pci/of.c (ffff8000106f9db0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f75c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-aardvark.c (ffff8000107204cc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722024)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff8000107238a4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724efc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff80001072595c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107261e8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727520)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727f5c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a06c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c72c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ec04)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff80001147a11c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091e2b4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffff80001093895c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e598)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (ffff800010944194)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/edac/altera_edac.c (ffff800010b16620)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
```
```
In drivers/of/irq.c (ffff800010b753bc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
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
In arch/arm/mach-exynos/suspend.c (c150c81c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init
  - arch/arm/mach-exynos/suspend.c:irq_find_host
```
```
In arch/arm/mach-imx/gpc.c (c150f210)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
  - arch/arm/mach-imx/gpc.c:irq_find_host
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c1515094)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
```
```
In kernel/irq/irqdomain.c (c03d331c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/irqchip/irq-al-fic.c (c1549778)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/irqchip/irq-alpine-msi.c (c08135d0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
```
```
In drivers/irqchip/exynos-combiner.c (c15499a4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_init
```
```
In drivers/irqchip/irq-tegra.c (c1549ea0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
  - drivers/irqchip/irq-tegra.c:irq_find_host
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c154a080)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-orion.c (c154a44c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
```
```
In drivers/irqchip/irq-omap-intc.c (c154a9f4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
```
```
In drivers/irqchip/irq-gic-v3.c (c154bd84)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:partition_domain_translate
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (c154d138)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (c154d288)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d48c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fbe4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-renesas-rza1.c (c08204c4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
```
```
In drivers/irqchip/irq-crossbar.c (c154dc1c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:irqcrossbar_init
  - drivers/irqchip/irq-crossbar.c:irq_find_host
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c154dd7c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c154e050)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-cirq.c (c154e22c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c154e390)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (c154e6b4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0822228)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
```
```
In drivers/irqchip/irq-meson-gpio.c (c154e868)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
```
```
In drivers/irqchip/qcom-pdc.c (c0822a70)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c08232d0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083aaf0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852628)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858da4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869a70)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (c086a64c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-tegra.c (c08718a8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/pci/of.c (c0892430)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a8364)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac638)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08af504)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b03cc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b27fc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b30ac)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b4e9c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b80b8)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c15524d8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf734)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init
```
```
In drivers/soc/dove/pmu.c (c158f3a8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
```
```
In drivers/soc/tegra/pmc.c (c093b634)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:irq_find_host
```
```
In drivers/base/regmap/regmap-irq.c (c0a035d4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (c0a20db0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/tps65217.c (c0a233dc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/twl6030-irq.c (c0a26f98)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (c0a2d28c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/of/irq.c (c0c57828)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
```
```
In drivers/memory/omap-gpmc.c (c0c71594)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe
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
In arch/powerpc/sysdev/mpic.c (c000000001358afc)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/sysdev/xics/xics-common.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In arch/powerpc/sysdev/xive/common.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c00000000135da8c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
```
```
In kernel/irq/irqdomain.c (c0000000001de84c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/irqchip/irq-al-fic.c (c0000000013a0d44)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/pci/of.c (c0000000008777c8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/pci/controller/pci-ftpci100.c (c000000000891484)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000892290)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c31a4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df620)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e6a60)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (c0000000009edaf0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/of/irq.c (c000000000c528e4)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
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
In kernel/irq/irqdomain.c (ffffffe00011b25e)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/irqchip/irq-al-fic.c (ffffffe00002a9ba)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002abf6)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
```
In drivers/pci/of.c (ffffffe0004ca03a)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6622)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6fa6)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8edc)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059d9a8)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad696)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b250a)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6caa)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/of/irq.c (ffffffe000728b6c)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069a86)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81116e7b)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a590a)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee8b3)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81701172)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81059de6)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81107b6b)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594aaa)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8ef3)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4f82)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069f36)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81114d6b)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5e9a)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171bf93)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730b52)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173aaa0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b6b6)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8112039b)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c029a)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817372f3)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174bf92)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755ee0)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irqdomain.h:281
Inline: True
```
</details>
</li>
</ul>

## Differences
