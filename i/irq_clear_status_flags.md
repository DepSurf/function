# Function: <code>irq_clear_status_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056327)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81058678)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff810e046c)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_associate
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In drivers/gpio/gpiolib.c (ffffffff81424899)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff814c7c57)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157baa9)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8158537b)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65912-irq.c (ffffffff81586815)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588aaf)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158bb53)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:558
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81595a5a)
Location: include/linux/irq.h:558
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b358)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810589a8)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff810e6cbf)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff8146e5e9)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff815186c7)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0d6a)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff815db45e)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815ddd88)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e0dce)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:587
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff815ea896)
Location: include/linux/irq.h:587
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd68a1)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b738)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff810ed6af)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81490649)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81544bd7)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd723)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81608135)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160aa18)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160da6b)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:604
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816176a6)
Location: include/linux/irq.h:604
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7601)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105ae88)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff810ed079)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81499d39)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81558a37)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816114d2)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8161bfbd)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161eb65)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81621b63)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:654
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8162b597)
Location: include/linux/irq.h:654
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff826bdfac)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f398)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff810f5a8f)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff814d8029)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff815bcde7)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679d72)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816846ad)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816873a5)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168a393)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:683
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81693ed7)
Location: include/linux/irq.h:683
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7d5f)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810624a5)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff810fde56)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff815075e2)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff815f5497)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b5837)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816c076f)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c340b)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c64a3)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:685
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816d0026)
Location: include/linux/irq.h:685
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e8a8)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810681a5)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff81109626)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff8151bb62)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81610577)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d6a97)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816e1baf)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e47fb)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e78a3)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:686
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816f1646)
Location: include/linux/irq.h:686
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b6771)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106b995)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff81112bf0)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81549ea7)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff816442f5)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817121d1)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8171b26c)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171de89)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81721061)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:699
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8172abc1)
Location: include/linux/irq.h:699
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9c34)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c235)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810988c9)
Location: include/linux/irq.h:717
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff8111ee80)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff8156b047)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff816668a5)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817364d1)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8173f55c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81742159)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817451c0)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8174edc1)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072a12)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81073555)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109dc19)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff8112a244)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_insert_irq
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff8160e229)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81715d55)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3cb7)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817fcffc)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ffd75)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81802f67)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:747
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8180d48d)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073e84)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8107cbf8)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810997e9)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff81125c24)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_insert_irq
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81634af9)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff817328c8)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81807917)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8180ea7c)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81811015)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813df7)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8181c41d)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81074911)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8107dcf8)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099ff9)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff8112711b)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81618579)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81716498)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec3e2)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817f32ac)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f5795)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f8507)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:762
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff817ff7dd)
Location: include/linux/irq.h:762
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81080dac)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8108c668)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa019)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff81147674)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81687815)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81793728)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81878fc2)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8187c1e9)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e925)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81881957)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:764
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81889ed5)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81090010)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8109cff8)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfa3a)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff8116b789)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff817a4aa3)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff818cc254)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c1500)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff819c4b79)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6e47)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819ca1bc)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:768
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff819d3183)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a501d)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff810b4078)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810db90a)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff811a059e)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
```
```
In drivers/gpio/gpiolib.c (ffffffff818bc7c3)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81a1d6e4)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b3b949)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3da05)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b4164c)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81b4d571)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8104)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7178)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e6e9a)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff811b2426)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
```
```
In drivers/gpio/gpiolib.c (ffffffff818ff933)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81a668f4)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b8ed37)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90e95)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b949bc)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81ba09e1)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af193)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff810be5b8)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef21a)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
```
```
In kernel/irq/irqdomain.c (ffffffff811c2207)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_locked
```
```
In drivers/gpio/gpiolib.c (ffffffff81947123)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9413)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81be2c57)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4e35)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be898c)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81bf4b41)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0878)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown
```
```
In kernel/irq/irqdomain.c (ffff800010184950)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/irqchip/irq-gic-v4.c (ffff800010675500)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_unmap_vlpi
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
```
```
In drivers/gpio/gpiolib.c (ffff8000106be914)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001148f27c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
```
```
In drivers/xen/events/events_base.c (ffff800010830364)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092de78)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tc3589x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffff80001093a990)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093da84)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffff8000109410b0)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffff80001094defc)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3a14)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/irqchip/irq-gic-v4.c (c081d8dc)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_unmap_vlpi
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
```
```
In drivers/gpio/gpiolib.c (c085e704)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/gpio/gpio-htc-egpio.c (c1550af4)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/dma/ipu/ipu_irq.c (c158ec90)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/asic3.c (c159930c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0a0f8bc)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tc3589x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tc6393xb.c (c0a13c18)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (c0a22bac)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65217.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (c0a264ec)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0a2aa68)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (c0a37f70)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba004)
Location: include/linux/irq.h:717
Inline: True
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be274)
Location: include/linux/irq.h:717
Inline: True
```
```
In kernel/irq/irqdomain.c (c0000000001ddbf8)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (c00000000083b940)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cd768)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tc3589x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (c0000000009e1fb8)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5b44)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea47c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (c0000000009fa63c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b818)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a57fc)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4b9a)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tc3589x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffe0005af344)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1bf6)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4ada)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffe0005bee90)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7c4c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106bd25)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff81117460)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81560807)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff8162c5d5)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81703260)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289fd0e)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c045)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff81108150)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff81551657)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d7060)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828bab4b)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c1d5)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In kernel/irq/irqdomain.c (ffffffff81115350)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f377)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff8165a6e5)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729991)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81732a1c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81735619)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81738680)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81742281)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828bac61)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106d8d5)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_free
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099d99)
Location: include/linux/irq.h:717
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff81120980)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_associate
```
```
In drivers/gpio/gpiolib.c (ffffffff815791f7)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
```
```
In drivers/xen/events/events_base.c (ffffffff81674cd5)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81744dd1)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm831x-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8174de5c)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750a59)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753c10)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8925-core.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8997-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/max8998-irq.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/tps6586x.c (0)
Location: include/linux/irq.h:717
Inline: True
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8175d6c1)
Location: include/linux/irq.h:717
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
</ul>

## Differences
