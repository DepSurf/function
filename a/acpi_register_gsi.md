# Function: <code>acpi_register_gsi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f4b0)
Location: arch/x86/kernel/acpi/boot.c:672
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_open
```
**Symbols:**

```
ffffffff8104f4b0-ffffffff8104f4c1: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f600)
Location: arch/x86/kernel/acpi/boot.c:679
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_open
```
**Symbols:**

```
ffffffff8104f600-ffffffff8104f611: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051e00)
Location: arch/x86/kernel/acpi/boot.c:683
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81051e00-ffffffff81051e11: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051920)
Location: arch/x86/kernel/acpi/boot.c:698
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
```
**Symbols:**

```
ffffffff81051920-ffffffff81051931: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81055590)
Location: arch/x86/kernel/acpi/boot.c:716
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
```
**Symbols:**

```
ffffffff81055590-ffffffff810555a7: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81058420)
Location: arch/x86/kernel/acpi/boot.c:722
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81058420-ffffffff81058437: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8105e040)
Location: arch/x86/kernel/acpi/boot.c:723
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8105e040-ffffffff8105e057: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061450)
Location: arch/x86/kernel/acpi/boot.c:706
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81061450-ffffffff81061467: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061ce0)
Location: arch/x86/kernel/acpi/boot.c:706
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81061ce0-ffffffff81061cf7: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81067c80)
Location: arch/x86/kernel/acpi/boot.c:707
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/mailbox/pcc.c:pcc_parse_subspace_irq
```
**Symbols:**

```
ffffffff81067c80-ffffffff81067c97: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81069980)
Location: arch/x86/kernel/acpi/boot.c:707
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/mailbox/pcc.c:pcc_parse_subspace_irq
```
**Symbols:**

```
ffffffff81069980-ffffffff81069997: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8106a460)
Location: arch/x86/kernel/acpi/boot.c:707
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff8106a460-ffffffff8106a477: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81074ca0)
Location: arch/x86/kernel/acpi/boot.c:705
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81074ca0-ffffffff81074cb7: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810836de)
Location: arch/x86/kernel/acpi/boot.c:773
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff810835e0-ffffffff81083603: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8109641e)
Location: arch/x86/kernel/acpi/boot.c:786
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_open
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81096300-ffffffff81096323: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8109953c)
Location: arch/x86/kernel/acpi/boot.c:795
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_open
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81099420-ffffffff81099443: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810a0d7c)
Location: arch/x86/kernel/acpi/boot.c:804
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_open
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff810a0c60-ffffffff810a0c83: acpi_register_gsi (STB_GLOBAL)
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
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/irq.c (ffff80001077c080)
Location: drivers/acpi/irq.c:51
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/arm64/iort.c:acpi_iort_register_irq
  - drivers/acpi/arm64/gtdt.c:map_gt_gsi
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffff80001077c080-ffff80001077c12c: acpi_register_gsi (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061860)
Location: arch/x86/kernel/acpi/boot.c:706
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81061860-ffffffff81061877: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051c30)
Location: arch/x86/kernel/acpi/boot.c:706
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81051c30-ffffffff81051c47: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061c80)
Location: arch/x86/kernel/acpi/boot.c:706
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81061c80-ffffffff81061c97: acpi_register_gsi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_gsi(struct device *dev, u32 gsi, int trigger, int polarity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81063240)
Location: arch/x86/kernel/acpi/boot.c:706
Inline: True
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/char/hpet.c:hpet_open
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81063240-ffffffff81063257: acpi_register_gsi (STB_GLOBAL)
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
