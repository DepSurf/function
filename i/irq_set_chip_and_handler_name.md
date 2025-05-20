# Function: <code>irq_set_chip_and_handler_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810de770)
Location: kernel/irq/chip.c:821
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810de770-ffffffff810de7a1: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e40d0)
Location: kernel/irq/chip.c:879
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff810e40d0-ffffffff810e4101: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea620)
Location: kernel/irq/chip.c:888
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff810ea620-ffffffff810ea651: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9d40)
Location: kernel/irq/chip.c:993
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff810e9d40-ffffffff810e9d71: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f2290)
Location: kernel/irq/chip.c:1016
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff810f2290-ffffffff810f22c1: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa6e0)
Location: kernel/irq/chip.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff810fa6e0-ffffffff810fa711: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105ea0)
Location: kernel/irq/chip.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff81105ea0-ffffffff81105ed1: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110f340)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff8110f340-ffffffff8110f375: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b600)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff8111b600-ffffffff8111b635: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127850)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff81127850-ffffffff8112790e: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123450)
Location: kernel/irq/chip.c:1075
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff81123450-ffffffff8112350e: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811237b0)
Location: kernel/irq/chip.c:1078
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff811237b0-ffffffff8112386e: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143d80)
Location: kernel/irq/chip.c:1078
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff81143d80-ffffffff81143e3e: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, const struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81168280)
Location: kernel/irq/chip.c:1076
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff81168280-ffffffff8116835c: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, const struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c770)
Location: kernel/irq/chip.c:1078
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff8119c770-ffffffff8119c84c: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, const struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae5f0)
Location: kernel/irq/chip.c:1093
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff811ae5f0-ffffffff811ae6cc: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, const struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811be1f0)
Location: kernel/irq/chip.c:1090
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff811be1f0-ffffffff811be2cc: irq_set_chip_and_handler_name (STB_GLOBAL)
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
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f640)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_map
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_map
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_map
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_map
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_map
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_legacy_map
  - drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_intx_map
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_init_legacy_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
  - drivers/edac/altera_edac.c:a10_eccmgr_irqdomain_map
```
**Symbols:**

```
ffff80001017f640-ffff80001017f698: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf864)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-rda-intc.c:rda_irq_map
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_domain_map
  - drivers/irqchip/irq-aspeed-vic.c:avic_map
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_map_irq_domain
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_irq_map
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_map
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pci-tegra.c:tegra_msi_map
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_intx_map
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_intx_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/asic3.c:asic3_irq_remove
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/tps65217.c:tps65217_irq_map
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
  - drivers/memory/omap-gpmc.c:gpmc_irq_map
  - drivers/memory/omap-gpmc.c:gpmc_irq_map
```
**Symbols:**

```
c03cf864-c03cf8a0: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001da0c0)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/i8259.c:i8259_host_map
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_map
  - arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_map
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_map
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
c0000000001da0c0-c0000000001da11c: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000117ac4)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffe000117ac4-ffffffe000117b12: irq_set_chip_and_handler_name (STB_GLOBAL)
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
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113be0)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
**Symbols:**

```
ffffffff81113be0-ffffffff81113c15: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811048f0)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
**Symbols:**

```
ffffffff811048f0-ffffffff81104925: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111ad0)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff81111ad0-ffffffff81111b05: irq_set_chip_and_handler_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_set_chip_and_handler_name(unsigned int irq, struct irq_chip *chip, irq_flow_handler_t handle, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111d090)
Location: kernel/irq/chip.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
**Symbols:**

```
ffffffff8111d090-ffffffff8111d0c5: irq_set_chip_and_handler_name (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct irq_chip *chip</code> ➡️ <code>const struct irq_chip *chip</code>
</li>
</ul>
</details>
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
