# Function: <code>irq_domain_create_linear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0f0a)
Location: include/linux/irqdomain.h:266
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e64da)
Location: include/linux/irqdomain.h:292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
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
In kernel/irq/irqdomain.c (ffffffff810ececa)
Location: include/linux/irqdomain.h:299
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/i2c/i2c-core.c (ffffffff8170e062)
Location: include/linux/irqdomain.h:299
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81058c5c)
Location: include/linux/irqdomain.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff810ec86a)
Location: include/linux/irqdomain.h:334
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817212f7)
Location: include/linux/irqdomain.h:334
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d13c)
Location: include/linux/irqdomain.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff810f50da)
Location: include/linux/irqdomain.h:343
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8179267d)
Location: include/linux/irqdomain.h:343
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81060113)
Location: include/linux/irqdomain.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff810fd4aa)
Location: include/linux/irqdomain.h:349
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8154942d)
Location: include/linux/irqdomain.h:349
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d508a)
Location: include/linux/irqdomain.h:349
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81065e83)
Location: include/linux/irqdomain.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81108f5a)
Location: include/linux/irqdomain.h:351
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fb28)
Location: include/linux/irqdomain.h:351
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fc1da)
Location: include/linux/irqdomain.h:351
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069632)
Location: include/linux/irqdomain.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8111252a)
Location: include/linux/irqdomain.h:353
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81590429)
Location: include/linux/irqdomain.h:353
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183d146)
Location: include/linux/irqdomain.h:353
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069fb2)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8111e7ba)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b2159)
Location: include/linux/irqdomain.h:360
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186eb45)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81070c22)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81129efa)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165bb19)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81942b64)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81071ffb)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff811258ba)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bf26)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817fa02f)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81948ecc)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072b0f)
Location: include/linux/irqdomain.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81125baa)
Location: include/linux/irqdomain.h:373
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ede6)
Location: include/linux/irqdomain.h:373
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817ded04)
Location: include/linux/irqdomain.h:373
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192c7a7)
Location: include/linux/irqdomain.h:373
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107ea22)
Location: include/linux/irqdomain.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8114634a)
Location: include/linux/irqdomain.h:370
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1996)
Location: include/linux/irqdomain.h:370
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8186a787)
Location: include/linux/irqdomain.h:370
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cf973)
Location: include/linux/irqdomain.h:370
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108e372)
Location: include/linux/irqdomain.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff8116a5fa)
Location: include/linux/irqdomain.h:384
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In kernel/irq/irq_sim.c (ffffffff8116c3ec)
Location: include/linux/irqdomain.h:384
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_domain_create_sim
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817faa76)
Location: include/linux/irqdomain.h:384
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b33ef)
Location: include/linux/irqdomain.h:384
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b31859)
Location: include/linux/irqdomain.h:384
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a2b12)
Location: include/linux/irqdomain.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irq_sim.c (ffffffff811a138c)
Location: include/linux/irqdomain.h:372
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_domain_create_sim
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81927279)
Location: include/linux/irqdomain.h:372
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b28286)
Location: include/linux/irqdomain.h:372
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc63a9)
Location: include/linux/irqdomain.h:372
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In kernel/irq/irq_sim.c (ffffffff811b319c)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_domain_create_sim
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b449)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b77da9)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e039)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In kernel/irq/irq_sim.c (ffffffff811c2feb)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_domain_create_sim
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4f29)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcbba8)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de3fc7)
Location: include/linux/irqdomain.h:375
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In kernel/irq/irqdomain.c (ffff800010184080)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c468)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010676048)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff800011476024)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a738)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff800011476370)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a0d4)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ec14)
Location: include/linux/irqdomain.h:360
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab21fc)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In kernel/irq/irqdomain.c (c03d321c)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/irqchip/irq-gic.c (c0815454)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
```
```
In drivers/irqchip/irq-partition-percpu.c (c081e1bc)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
```
```
In drivers/irqchip/irq-rda-intc.c (c154d690)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda8810_intc_init
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b4f08)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b80cc)
Location: include/linux/irqdomain.h:360
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c0b9399c)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b95aa0)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In kernel/irq/irqdomain.c (ffffffe00011b144)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8ee6)
Location: include/linux/irqdomain.h:360
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9ffa)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069aa2)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81116d9a)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5919)
Location: include/linux/irqdomain.h:360
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81059e02)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81107a8a)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594ab9)
Location: include/linux/irqdomain.h:360
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069f52)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff81114c8a)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5ea9)
Location: include/linux/irqdomain.h:360
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81862cd5)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b6d2)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In kernel/irq/irqdomain.c (ffffffff811202ba)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c02a9)
Location: include/linux/irqdomain.h:360
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187df35)
Location: include/linux/irqdomain.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
</ul>

## Differences
