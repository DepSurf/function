# Function: <code>irq_domain_set_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0fc0)
Location: kernel/irq/irqdomain.c:1055
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
ffffffff810e0fc0-ffffffff810e0ff6: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6250)
Location: kernel/irq/irqdomain.c:1104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
ffffffff810e6250-ffffffff810e6286: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecc40)
Location: kernel/irq/irqdomain.c:1130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
ffffffff810ecc40-ffffffff810ecc76: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec5e0)
Location: kernel/irq/irqdomain.c:1299
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
ffffffff810ec5e0-ffffffff810ec616: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4770)
Location: kernel/irq/irqdomain.c:1299
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
ffffffff810f4770-ffffffff810f47a6: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fcb70)
Location: kernel/irq/irqdomain.c:1183
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff810fcb70-ffffffff810fcba6: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108420)
Location: kernel/irq/irqdomain.c:1183
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81108420-ffffffff81108456: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111a20)
Location: kernel/irq/irqdomain.c:1220
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81111a20-ffffffff81111a5b: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111dc90)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff8111dc90-ffffffff8111dccb: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a830)
Location: kernel/irq/irqdomain.c:1236
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff8112a830-ffffffff8112a8bd: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811263e0)
Location: kernel/irq/irqdomain.c:1342
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff811263e0-ffffffff8112646d: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126400)
Location: kernel/irq/irqdomain.c:1309
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81126400-ffffffff8112648d: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146740)
Location: kernel/irq/irqdomain.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81146740-ffffffff811467cd: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116aa90)
Location: kernel/irq/irqdomain.c:1352
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff8116aa90-ffffffff8116ab2e: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f6c0)
Location: kernel/irq/irqdomain.c:1412
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff8119f6c0-ffffffff8119f75e: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1c70)
Location: kernel/irq/irqdomain.c:1391
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff811b1c70-ffffffff811b1d0e: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1a20)
Location: kernel/irq/irqdomain.c:1391
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff811c1a20-ffffffff811c1abe: irq_domain_set_info (STB_GLOBAL)
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
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183270)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffff800010183270-ffff800010183300: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d25ac)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
c03d25ac-c03d25fc: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001df560)
Location: kernel/irq/irqdomain.c:1722
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
c0000000001df560-c0000000001df5e8: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a64a)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffe00011a64a-ffffffe00011a6c2: irq_domain_set_info (STB_GLOBAL)
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
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116270)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81116270-ffffffff811162ab: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106f60)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81106f60-ffffffff81106f9b: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114160)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff81114160-ffffffff8111419b: irq_domain_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip *chip, void *chip_data, irq_flow_handler_t handler, void *handler_data, const char *handler_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f790)
Location: kernel/irq/irqdomain.c:1222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/kernel/apic/msi.c:dmar_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffff8111f790-ffffffff8111f7cb: irq_domain_set_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct irq_chip *chip</code> ➡️ <code>const struct irq_chip *chip</code>
</li>
</ul>
</details>
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
