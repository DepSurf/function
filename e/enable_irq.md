# Function: <code>enable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dc390)
Location: kernel/irq/manage.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_suspend_late
  - drivers/mfd/arizona-core.c:arizona_suspend_late
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
**Symbols:**

```
ffffffff810dc390-ffffffff810dc427: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1aa0)
Location: kernel/irq/manage.c:560
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_resume
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_late
  - drivers/mfd/arizona-core.c:arizona_suspend_late
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_stop_interrupts
```
**Symbols:**

```
ffffffff810e1aa0-ffffffff810e1b37: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e83d0)
Location: kernel/irq/manage.c:560
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff810e83d0-ffffffff810e8467: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7910)
Location: kernel/irq/manage.c:537
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff810e7910-ffffffff810e799d: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810efc90)
Location: kernel/irq/manage.c:565
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff810efc90-ffffffff810efd1d: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f80d0)
Location: kernel/irq/manage.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff810f80d0-ffffffff810f815d: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81103870)
Location: kernel/irq/manage.c:601
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81103870-ffffffff811038fd: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110c2b0)
Location: kernel/irq/manage.c:645
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff8110c2b0-ffffffff8110c33f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118690)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81118690-ffffffff8111871f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81123f80)
Location: kernel/irq/manage.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81123f80-ffffffff8112400f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fde0)
Location: kernel/irq/manage.c:784
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff8111fde0-ffffffff8111fe6f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120090)
Location: kernel/irq/manage.c:784
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81120090-ffffffff8112011f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811405c0)
Location: kernel/irq/manage.c:808
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff811405c0-ffffffff8114064f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163f70)
Location: kernel/irq/manage.c:823
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81163f70-ffffffff81164013: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81197ce0)
Location: kernel/irq/manage.c:815
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81197ce0-ffffffff81197d83: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a99a0)
Location: kernel/irq/manage.c:821
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff811a99a0-ffffffff811a9a43: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b9500)
Location: kernel/irq/manage.c:823
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff811b9500-ffffffff811b95a3: enable_irq (STB_GLOBAL)
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
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017af88)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_enable_doorbell
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller
  - drivers/net/ethernet/smsc/smc91x.c:smc_poll_controller
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/perf/arm_pmu.c:arm_perf_starting_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
```
**Symbols:**

```
ffff80001017af88-ffff80001017b02c: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cc0c8)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/arm/kernel/fiq.c:enable_fiq
  - kernel/irq/manage.c:enable_nmi
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_work
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_resume
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
  - drivers/clocksource/exynos_mct.c:exynos4_mct_starting_cpu
  - drivers/perf/arm_pmu.c:arm_perf_starting_cpu
```
**Symbols:**

```
c03cc0c8-c03cc178: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d5570)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
  - kernel/irq/manage.c:enable_nmi
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77620.c:max77620_i2c_resume
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
```
**Symbols:**

```
c0000000001d5570-c0000000001d5634: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114be2)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max8997.c:max8997_resume
```
**Symbols:**

```
ffffffe000114be2-ffffffe000114c4e: enable_irq (STB_GLOBAL)
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
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81110c70)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
```
**Symbols:**

```
ffffffff81110c70-ffffffff81110cff: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811019a0)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
```
**Symbols:**

```
ffffffff811019a0-ffffffff81101a2f: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110eb60)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff8110eb60-ffffffff8110ebef: enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111a090)
Location: kernel/irq/manage.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:enable_nmi
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check
  - drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_resume
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend_noirq
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl-core.c:twl_resume
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/da9052-irq.c:da9052_enable_irq
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/tps6586x.c:tps6586x_i2c_resume
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff8111a090-ffffffff8111a11f: enable_irq (STB_GLOBAL)
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
