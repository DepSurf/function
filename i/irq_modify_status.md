# Function: <code>irq_modify_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810dd990)
Location: kernel/irq/chip.c:829
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810dd990-ffffffff810dda83: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e31a0)
Location: kernel/irq/chip.c:887
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810e31a0-ffffffff810e3293: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9a80)
Location: kernel/irq/chip.c:896
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810e9a80-ffffffff810e9b5a: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e8f70)
Location: kernel/irq/chip.c:1001
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810e8f70-ffffffff810e9076: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f13d0)
Location: kernel/irq/chip.c:1024
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810f13d0-ffffffff810f14d6: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f9810)
Location: kernel/irq/chip.c:1022
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810f9810-ffffffff810f9916: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104fc0)
Location: kernel/irq/chip.c:1022
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff81104fc0-ffffffff811050c6: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e2a0)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff8110e2a0-ffffffff8110e3ac: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a560)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff8111a560-ffffffff8111a66c: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811265e0)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_insert_irq
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff811265e0-ffffffff811266ec: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122220)
Location: kernel/irq/chip.c:1083
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_insert_irq
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff81122220-ffffffff8112231f: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811225a0)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff811225a0-ffffffff8112269f: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81142b50)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff81142b50-ffffffff81142c4f: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811667f0)
Location: kernel/irq/chip.c:1084
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff811667f0-ffffffff81166905: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119aaa0)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff8119aaa0-ffffffff8119abb5: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ac800)
Location: kernel/irq/chip.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff811ac800-ffffffff811ac915: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bc400)
Location: kernel/irq/chip.c:1098
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/hpet.c:hpet_msi_free
  - arch/x86/kernel/hpet.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff811bc400-ffffffff811bc515: irq_modify_status (STB_GLOBAL)
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017dbc8)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v4.c:its_unmap_vlpi
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_map
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_legacy_map
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/edac/altera_edac.c:a10_eccmgr_irqdomain_map
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
```
**Symbols:**

```
ffff80001017dbc8-ffff80001017dd10: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03ce3a4)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v4.c:its_unmap_vlpi
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-rda-intc.c:rda_irq_map
  - drivers/irqchip/irq-rda-intc.c:rda_irq_map
  - drivers/irqchip/irq-aspeed-vic.c:avic_map
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_irq_remove
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_detach_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/tps65217.c:tps65217_irq_map
  - drivers/mfd/tps65217.c:tps65217_irq_map
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/memory/omap-gpmc.c:gpmc_irq_map
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
**Symbols:**

```
c03ce3a4-c03ce51c: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d84b0)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/powerpc/sysdev/i8259.c:i8259_host_map
  - arch/powerpc/sysdev/i8259.c:i8259_host_map
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
c0000000001d84b0-c0000000001d8630: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001167ec)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffe0001167ec-ffffffe0001168d6: irq_modify_status (STB_GLOBAL)
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112b40)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81112b40-ffffffff81112c4c: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81103860)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irq_sim.c:irq_sim_init
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81103860-ffffffff8110396c: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81110a30)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff81110a30-ffffffff81110b3c: irq_modify_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111bfb0)
Location: kernel/irq/chip.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff8111bfb0-ffffffff8111c0bc: irq_modify_status (STB_GLOBAL)
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
