# Function: <code>irq_set_handler_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810dd8b0)
Location: kernel/irq/chip.c:93
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff810dd8b0-ffffffff810dd918: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e30c0)
Location: kernel/irq/chip.c:93
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff810e30c0-ffffffff810e3128: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e99a0)
Location: kernel/irq/chip.c:92
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff810e99a0-ffffffff810e9a08: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e8e90)
Location: kernel/irq/chip.c:92
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff810e8e90-ffffffff810e8ef8: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f12f0)
Location: kernel/irq/chip.c:92
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff810f12f0-ffffffff810f1358: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f9730)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff810f9730-ffffffff810f9798: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104ee0)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff81104ee0-ffffffff81104f48: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e1c0)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff8110e1c0-ffffffff8110e228: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a480)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff8111a480-ffffffff8111a4e8: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81126500)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff81126500-ffffffff81126567: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122140)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff81122140-ffffffff811221a7: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811224c0)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff811224c0-ffffffff81122527: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81142a70)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff81142a70-ffffffff81142ad7: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811666f0)
Location: kernel/irq/chip.c:87
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff811666f0-ffffffff8116676b: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119a980)
Location: kernel/irq/chip.c:87
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff8119a980-ffffffff8119a9fb: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ac6e0)
Location: kernel/irq/chip.c:87
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff811ac6e0-ffffffff811ac75b: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bc2e0)
Location: kernel/irq/chip.c:87
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff811bc2e0-ffffffff811bc35b: irq_set_handler_data (STB_GLOBAL)
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
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017dab8)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_map
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffff80001017dab8-ffff80001017db40: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03ce294)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
c03ce294-c03ce31c: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d8370)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/xive/common.c:xive_irq_domain_unmap
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
c0000000001d8370-c0000000001d840c: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000116748)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffe000116748-ffffffe00011679a: irq_set_handler_data (STB_GLOBAL)
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
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112a60)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
```
**Symbols:**

```
ffffffff81112a60-ffffffff81112ac8: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81103780)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff81103780-ffffffff811037e8: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81110950)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff81110950-ffffffff811109b8: irq_set_handler_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_handler_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111bed0)
Location: kernel/irq/chip.c:90
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
**Symbols:**

```
ffffffff8111bed0-ffffffff8111bf38: irq_set_handler_data (STB_GLOBAL)
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
