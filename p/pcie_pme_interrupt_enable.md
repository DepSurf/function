# Function: <code>pcie_pme_interrupt_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8144b6f7)
Location: drivers/pci/pcie/pme.c:62
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff8144b960-ffffffff8144b97c: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff8144bee0-ffffffff8144bf08: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81497e18)
Location: drivers/pci/pcie/pme.c:62
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff81497bf0-ffffffff81497c0c: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff81498180-ffffffff814981a8: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff814b96c8)
Location: drivers/pci/pcie/pme.c:61
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff814b9530-ffffffff814b954c: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff814b9a30-ffffffff814b9a58: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff814c3eb1)
Location: drivers/pci/pcie/pme.c:55
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff814c3d20-ffffffff814c3d3c: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff814c4200-ffffffff814c4228: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815040f1)
Location: drivers/pci/pcie/pme.c:55
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff81503f60-ffffffff81503f7c: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff81504450-ffffffff81504478: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81534f3e)
Location: drivers/pci/pcie/pme.c:51
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff81534dd0-ffffffff81534dec: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff815353a0-ffffffff815353c8: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8154c5de)
Location: drivers/pci/pcie/pme.c:51
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff8154c470-ffffffff8154c48c: pcie_pme_interrupt_enable.part.7 (STB_LOCAL)
ffffffff8154c950-ffffffff8154c978: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8157c6d1)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff8157c170-ffffffff8157c18c: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffff8157c710-ffffffff8157c738: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8159e131)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff8159dbd0-ffffffff8159dbec: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffff8159e170-ffffffff8159e198: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8163db91)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff8163ddd0-ffffffff8163de04: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81664221)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff81664460-ffffffff81664494: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81646691)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff816468d0-ffffffff81646904: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff816b7e91)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff816b8170-ffffffff816b81a4: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff817dc1d1)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff817dc590-ffffffff817dc5e0: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff818fe0c1)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
**Symbols:**

```
ffffffff818fe680-ffffffff818fe6d0: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81941571)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
**Symbols:**

```
ffffffff81941b30-ffffffff81941b80: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8198a7d1)
Location: drivers/pci/pcie/pme.c:54
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
**Symbols:**

```
ffffffff8198adc0-ffffffff8198ae10: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffff80001070604c)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffff800010705bb8-ffff800010705bf0: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffff800010706440-ffff800010706490: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (c089cf58)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
c089cef4-c089cf1c: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
c089d3f8-c089d42c: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffe0004d4148)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffe0004d3aa2-ffffffe0004d3ad2: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffe0004d41b6-ffffffe0004d4206: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81591931)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff815913d0-ffffffff815913ec: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffff81591970-ffffffff81591998: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81580ae1)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff815805a0-ffffffff815805bc: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffff81580b10-ffffffff81580b38: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81591e81)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff81591920-ffffffff8159193c: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffff81591ec0-ffffffff81591ee8: pcie_pme_interrupt_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815abf61)
Location: drivers/pci/pcie/pme.c:53
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff815abf10-ffffffff815abf2c: pcie_pme_interrupt_enable.part.0 (STB_LOCAL)
ffffffff815ac340-ffffffff815ac368: pcie_pme_interrupt_enable (STB_GLOBAL)
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
