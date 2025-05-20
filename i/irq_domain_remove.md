# Function: <code>irq_domain_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0250)
Location: kernel/irq/irqdomain.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/base/regmap/regmap-irq.c:regmap_del_irq_chip
```
**Symbols:**

```
ffffffff810e0250-ffffffff810e0324: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5c40)
Location: kernel/irq/irqdomain.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810e5c40-ffffffff810e5cef: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec630)
Location: kernel/irq/irqdomain.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810ec630-ffffffff810ec6df: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebf70)
Location: kernel/irq/irqdomain.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff810ebf70-ffffffff810ec00f: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4450)
Location: kernel/irq/irqdomain.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff810f4450-ffffffff810f44ef: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc840)
Location: kernel/irq/irqdomain.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff810fc840-ffffffff810fc8f5: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811080f0)
Location: kernel/irq/irqdomain.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff811080f0-ffffffff811081a5: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff811132a5-ffffffff811132b8: irq_domain_remove.cold (STB_LOCAL)
ffffffff81111730-ffffffff811117ea: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d990)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff8111d990-ffffffff8111da51: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112ace0)
Location: kernel/irq/irqdomain.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff8112ace0-ffffffff8112adc9: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126890)
Location: kernel/irq/irqdomain.c:237
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff81126890-ffffffff81126979: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811268b0)
Location: kernel/irq/irqdomain.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811268b0-ffffffff811269b3: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146eb0)
Location: kernel/irq/irqdomain.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff81146eb0-ffffffff81146fad: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b2a0)
Location: kernel/irq/irqdomain.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff8116b2a0-ffffffff8116b3ad: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0070)
Location: kernel/irq/irqdomain.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811a0070-ffffffff811a0180: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1f30)
Location: kernel/irq/irqdomain.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811b1f30-ffffffff811b2040: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1ce0)
Location: kernel/irq/irqdomain.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811c1ce0-ffffffff811c1df0: irq_domain_remove (STB_GLOBAL)
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
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010182e80)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_remove
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-altera.c:altera_pcie_remove
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
**Symbols:**

```
ffff800010182e80-ffff800010182f8c: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d21e0)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_remove
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi
  - drivers/pci/controller/pcie-altera.c:altera_pcie_remove
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65217.c:tps65217_remove
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/memory/omap-gpmc.c:gpmc_remove
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
**Symbols:**

```
c03d21e0-c03d2320: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dd900)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
**Symbols:**

```
c0000000001dd900-c0000000001dda88: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a2ea)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
**Symbols:**

```
ffffffe00011a2ea-ffffffe00011a40c: irq_domain_remove (STB_GLOBAL)
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
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115f70)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81115f70-ffffffff81116031: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106c60)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81106c60-ffffffff81106d21: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113e60)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81113e60-ffffffff81113f21: irq_domain_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f480)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff8111f480-ffffffff8111f541: irq_domain_remove (STB_GLOBAL)
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
