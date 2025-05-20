# Function: <code>disable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810daed0)
Location: kernel/irq/manage.c:480
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/net/phy/phy.c:phy_change
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff810daed0-ffffffff810daeef: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0560)
Location: kernel/irq/manage.c:494
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_resume
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/net/phy/phy.c:phy_change
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff810e0560-ffffffff810e057f: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6eb0)
Location: kernel/irq/manage.c:494
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/net/phy/phy.c:phy_change
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff810e6eb0-ffffffff810e6ecf: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e65b0)
Location: kernel/irq/manage.c:465
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/net/phy/phy.c:phy_change
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff810e65b0-ffffffff810e65cf: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee860)
Location: kernel/irq/manage.c:493
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff810ee860-ffffffff810ee87f: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6c50)
Location: kernel/irq/manage.c:526
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff810f6c50-ffffffff810f6c72: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811023c0)
Location: kernel/irq/manage.c:529
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_work
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff811023c0-ffffffff811023e2: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110abd0)
Location: kernel/irq/manage.c:558
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8110abd0-ffffffff8110abf7: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116fa0)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81116fa0-ffffffff81116fc7: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81125560)
Location: kernel/irq/manage.c:627
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81125560-ffffffff8112558b: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811213c0)
Location: kernel/irq/manage.c:697
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff811213c0-ffffffff811213eb: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811216a0)
Location: kernel/irq/manage.c:697
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff811216a0-ffffffff811216cb: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141c40)
Location: kernel/irq/manage.c:721
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81141c40-ffffffff81141c6b: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81165750)
Location: kernel/irq/manage.c:736
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81165750-ffffffff81165788: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81199690)
Location: kernel/irq/manage.c:728
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_suspend
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81199690-ffffffff811996c8: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab370)
Location: kernel/irq/manage.c:733
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_suspend
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff811ab370-ffffffff811ab3af: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bb300)
Location: kernel/irq/manage.c:735
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_suspend
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/i2c/i2c-core-base.c:i2c_device_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff811bb300-ffffffff811bb34c: disable_irq (STB_GLOBAL)
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
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010179768)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_disable_doorbell
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77686.c:max77686_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/as3722.c:as3722_i2c_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller
  - drivers/net/ethernet/smsc/smc91x.c:smc_poll_controller
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
```
**Symbols:**

```
ffff800010179768-ffff8000101797ac: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca9e0)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/arm/kernel/fiq.c:disable_fiq
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77686.c:max77686_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/as3722.c:as3722_i2c_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/power/avs/smartreflex.c:sr_late_init
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_pause
```
**Symbols:**

```
c03ca9e0-c03caa10: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d3480)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77620.c:max77620_i2c_suspend
  - drivers/mfd/max77686.c:max77686_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/as3722.c:as3722_i2c_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
c0000000001d3480-c0000000001d34e8: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000113a1a)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffe000113a1a-ffffffe000113a5a: disable_irq (STB_GLOBAL)
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
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f580)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8110f580-ffffffff8110f5a7: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811002c0)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
```
**Symbols:**

```
ffffffff811002c0-ffffffff811002e7: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d470)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff8110d470-ffffffff8110d497: disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void disable_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811189d0)
Location: kernel/irq/manage.c:551
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/arizona-core.c:arizona_suspend
  - drivers/mfd/twl-core.c:twl_suspend
  - drivers/mfd/da9052-irq.c:da9052_disable_irq
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/tps6586x.c:tps6586x_i2c_suspend
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff811189d0-ffffffff811189f7: disable_irq (STB_GLOBAL)
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
