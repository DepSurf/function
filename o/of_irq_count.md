# Function: <code>of_irq_count</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_irq_count(struct device_node *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b752b8)
Location: drivers/of/irq.c:433
Inline: False
Direct callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffff800010b752b8-ffff800010b75330: of_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_irq_count(struct device_node *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c5773c)
Location: drivers/of/irq.c:433
Inline: False
Direct callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c0c5773c-c0c577b8: of_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_irq_count(struct device_node *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c527c0)
Location: drivers/of/irq.c:433
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c000000000c527c0-c000000000c52858: of_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_irq_count(struct device_node *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe000728ac0)
Location: drivers/of/irq.c:433
Inline: False
Direct callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffffffe000728ac0-ffffffe000728afe: of_irq_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
