# Function: <code>generic_handle_domain_irq</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain *domain, unsigned int hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113dd80)
Location: kernel/irq/irqdesc.c:673
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff8113dd80-ffffffff8113dd9c: generic_handle_domain_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain *domain, unsigned int hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161b00)
Location: kernel/irq/irqdesc.c:702
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff81161b00-ffffffff81161b26: generic_handle_domain_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain *domain, unsigned int hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195240)
Location: kernel/irq/irqdesc.c:705
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff81195240-ffffffff81195266: generic_handle_domain_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain *domain, unsigned int hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6bd0)
Location: kernel/irq/irqdesc.c:726
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff811a6bd0-ffffffff811a6bf6: generic_handle_domain_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain *domain, unsigned int hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b66f0)
Location: kernel/irq/irqdesc.c:726
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff811b66f0-ffffffff811b6716: generic_handle_domain_irq (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
