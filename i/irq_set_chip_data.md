# Function: <code>irq_set_chip_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810dd920)
Location: kernel/irq/chip.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff810dd920-ffffffff810dd988: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e3130)
Location: kernel/irq/chip.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff810e3130-ffffffff810e3198: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9a10)
Location: kernel/irq/chip.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff810e9a10-ffffffff810e9a78: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e8f00)
Location: kernel/irq/chip.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff810e8f00-ffffffff810e8f68: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1360)
Location: kernel/irq/chip.c:147
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff810f1360-ffffffff810f13c8: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f97a0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff810f97a0-ffffffff810f9808: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104f50)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff81104f50-ffffffff81104fb8: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e230)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff8110e230-ffffffff8110e298: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a4f0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff8111a4f0-ffffffff8111a558: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81126570)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff81126570-ffffffff811265d7: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811221b0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff811221b0-ffffffff81122217: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122530)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff81122530-ffffffff81122597: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81142ae0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff81142ae0-ffffffff81142b47: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81166770)
Location: kernel/irq/chip.c:142
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff81166770-ffffffff811667eb: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119aa10)
Location: kernel/irq/chip.c:142
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff8119aa10-ffffffff8119aa8b: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ac770)
Location: kernel/irq/chip.c:142
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff811ac770-ffffffff811ac7eb: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bc370)
Location: kernel/irq/chip.c:142
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:delayed_free_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff811bc370-ffffffff811bc3eb: irq_set_chip_data (STB_GLOBAL)
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
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017db40)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
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
  - drivers/pci/msi.c:arch_setup_msi_irq
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
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/edac/altera_edac.c:a10_eccmgr_irqdomain_map
```
**Symbols:**

```
ffff80001017db40-ffff80001017dbc8: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03ce31c)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
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
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pci-tegra.c:tegra_msi_map
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_intx_map
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_intx_map
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_irq_remove
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_detach_irq
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_detach_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/tps65217.c:tps65217_irq_map
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
  - drivers/memory/omap-gpmc.c:gpmc_irq_map
```
**Symbols:**

```
c03ce31c-c03ce3a4: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d8410)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_map
  - arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_map
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_map
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
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
c0000000001d8410-c0000000001d84ac: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe00011679a)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
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
ffffffe00011679a-ffffffe0001167ec: irq_set_chip_data (STB_GLOBAL)
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
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112ad0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81112ad0-ffffffff81112b38: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811037f0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_init
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff811037f0-ffffffff81103858: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811109c0)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff811109c0-ffffffff81110a28: irq_set_chip_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111bf40)
Location: kernel/irq/chip.c:145
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/pci/msi.c:arch_setup_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/arizona-irq.c:arizona_irq_map
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
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
ffffffff8111bf40-ffffffff8111bfa8: irq_set_chip_data (STB_GLOBAL)
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
