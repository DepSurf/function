# Function: <code>disable_irq_nosync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810daec0)
Location: kernel/irq/manage.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810daec0-ffffffff810daed0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0550)
Location: kernel/irq/manage.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810e0550-ffffffff810e0560: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6ea0)
Location: kernel/irq/manage.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810e6ea0-ffffffff810e6eb0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e65a0)
Location: kernel/irq/manage.c:447
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810e65a0-ffffffff810e65b0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee850)
Location: kernel/irq/manage.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810ee850-ffffffff810ee860: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6c40)
Location: kernel/irq/manage.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810f6c40-ffffffff810f6c50: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811023b0)
Location: kernel/irq/manage.c:511
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff811023b0-ffffffff811023c0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d8d8)
Location: kernel/irq/manage.c:540
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff8110ab90-ffffffff8110aba0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111953b)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81116f60-ffffffff81116f70: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81124ddb)
Location: kernel/irq/manage.c:609
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81122de0-ffffffff81122df0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120c3b)
Location: kernel/irq/manage.c:679
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8111ec70-ffffffff8111ec80: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120f0b)
Location: kernel/irq/manage.c:679
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8111eef0-ffffffff8111ef00: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8114148b)
Location: kernel/irq/manage.c:703
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8113f1b0-ffffffff8113f1c0: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81164eac)
Location: kernel/irq/manage.c:718
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81162af0-ffffffff81162b08: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81198cec)
Location: kernel/irq/manage.c:710
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/acpi/ec.c:acpi_ec_mask_events
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff811966a0-ffffffff811966b8: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811aa9cc)
Location: kernel/irq/manage.c:713
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/acpi/ec.c:acpi_ec_mask_events
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff811a8060-ffffffff811a8078: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ba5ac)
Location: kernel/irq/manage.c:715
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/acpi/ec.c:acpi_ec_mask_events
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff811b7bc0-ffffffff811b7bd8: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c110)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/video/fbdev/mx3fb.c:mx3fb_dma_done
  - drivers/video/fbdev/mx3fb.c:mx3fb_dma_done
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/thermal/armada_thermal.c:armada_overheat_isr
```
**Symbols:**

```
ffff800010178ef0-ffff800010178f1c: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cd154)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_dma_done
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mtd/nand/raw/omap2.c:omap_nand_irq
  - drivers/mtd/nand/raw/omap2.c:omap_nand_irq
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_irq
  - drivers/thermal/armada_thermal.c:armada_overheat_isr
  - drivers/clocksource/timer-tegra.c:tegra_timer_stop
```
**Symbols:**

```
c03ca98c-c03ca9a8: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d6c78)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_event
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_int_handler
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
c0000000001d33f0-c0000000001d3404: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001158c0)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffe0001139ae-ffffffe0001139d8: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81111b1b)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
```
**Symbols:**

```
ffffffff8110f540-ffffffff8110f550: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110284b)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81100280-ffffffff81100290: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110fa0b)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff8110d430-ffffffff8110d440: disable_irq_nosync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111af3b)
Location: kernel/irq/manage.c:533
Inline: True
Inline callers:
  - kernel/irq/manage.c:free_nmi
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/da903x.c:da903x_irq_handler
  - drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask
```
**Symbols:**

```
ffffffff81118990-ffffffff811189a0: disable_irq_nosync (STB_GLOBAL)
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
