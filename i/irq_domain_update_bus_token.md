# Function: <code>irq_domain_update_bus_token</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810eca70)
Location: kernel/irq/irqdomain.c:264
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810eca70-ffffffff810ecaf4: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f54d0)
Location: kernel/irq/irqdomain.c:265
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810f54d0-ffffffff810f5554: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd8a0)
Location: kernel/irq/irqdomain.c:267
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff810fd8a0-ffffffff810fd916: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109070)
Location: kernel/irq/irqdomain.c:267
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81109070-ffffffff811090e6: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112650)
Location: kernel/irq/irqdomain.c:267
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81112650-ffffffff811126c5: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111e8e0)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff8111e8e0-ffffffff8111e955: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112add0)
Location: kernel/irq/irqdomain.c:254
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff8112add0-ffffffff8112ae45: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125560)
Location: kernel/irq/irqdomain.c:263
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81125560-ffffffff811255d5: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125830)
Location: kernel/irq/irqdomain.c:265
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81125830-ffffffff811258a5: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81145fc0)
Location: kernel/irq/irqdomain.c:275
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81145fc0-ffffffff81146035: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a230)
Location: kernel/irq/irqdomain.c:275
Inline: True
Direct callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8116a230-ffffffff8116a2c1: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119ecf0)
Location: kernel/irq/irqdomain.c:299
Inline: True
Direct callers:
  - kernel/irq/msi.c:__msi_create_irq_domain
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff8119ecf0-ffffffff8119ed81: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b0b40)
Location: kernel/irq/irqdomain.c:306
Inline: True
Direct callers:
  - kernel/irq/msi.c:__msi_create_irq_domain
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff811b0b40-ffffffff811b0bd1: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c08c0)
Location: kernel/irq/irqdomain.c:306
Inline: True
Direct callers:
  - kernel/irq/msi.c:__msi_create_irq_domain
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
**Symbols:**

```
ffffffff811c08c0-ffffffff811c0951: irq_domain_update_bus_token (STB_GLOBAL)
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
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184230)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_msi_create_irq_domain
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/soc/ti/ti_sci_inta_msi.c:ti_sci_inta_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffff800010184230-ffff8000101842cc: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3374)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
c03d3374-c03d3400: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dea10)
Location: kernel/irq/irqdomain.c:269
Inline: False
```
**Symbols:**

```
c0000000001dea10-c0000000001deaf0: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b2a6)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffe00011b2a6-ffffffe00011b336: irq_domain_update_bus_token (STB_GLOBAL)
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
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116ec0)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81116ec0-ffffffff81116f35: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107bb0)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81107bb0-ffffffff81107c25: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114db0)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff81114db0-ffffffff81114e25: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_update_bus_token(struct irq_domain *domain, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811203e0)
Location: kernel/irq/irqdomain.c:269
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_irq_domain
```
**Symbols:**

```
ffffffff811203e0-ffffffff81120455: irq_domain_update_bus_token (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
