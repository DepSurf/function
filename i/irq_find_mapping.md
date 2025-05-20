# Function: <code>irq_find_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0750)
Location: kernel/irq/irqdomain.c:654
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810e0750-ffffffff810e07f2: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e61a0)
Location: kernel/irq/irqdomain.c:697
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
**Symbols:**

```
ffffffff810e61a0-ffffffff810e6242: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecb90)
Location: kernel/irq/irqdomain.c:720
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/i2c/i2c-core.c:i2c_handle_smbus_host_notify
  - drivers/i2c/i2c-core.c:i2c_device_probe
```
**Symbols:**

```
ffffffff810ecb90-ffffffff810ecc32: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec530)
Location: kernel/irq/irqdomain.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff810ec530-ffffffff810ec5de: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f46b0)
Location: kernel/irq/irqdomain.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff810f46b0-ffffffff810f4761: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fcac0)
Location: kernel/irq/irqdomain.c:874
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff810fcac0-ffffffff810fcb69: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108370)
Location: kernel/irq/irqdomain.c:874
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81108370-ffffffff81108419: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111980)
Location: kernel/irq/irqdomain.c:891
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81111980-ffffffff81111a1c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111dbf0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8111dbf0-ffffffff8111dc8c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112aa70)
Location: kernel/irq/irqdomain.c:878
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8112aa70-ffffffff8112ab0c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126670)
Location: kernel/irq/irqdomain.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81126670-ffffffff81126718: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126690)
Location: kernel/irq/irqdomain.c:869
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81126690-ffffffff81126738: irq_find_mapping (STB_GLOBAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81080b8a)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
```
```
In kernel/irq/generic-chip.c (ffffffff81144ccd)
Location: include/linux/irqdomain.h:420
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff81147a39)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In kernel/irq/msi.c (ffffffff811498c6)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167e8ed)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816848ea)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff816886cf)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81692623)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff818695f7)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a378)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
```
In drivers/mfd/twl6030-irq.c (ffffffff8187ec92)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818835d8)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
```
```
In drivers/mfd/max8997-irq.c (ffffffff81886094)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
```
```
In drivers/mfd/max8998-irq.c (ffffffff81886f6d)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
```
In drivers/mfd/tps6586x.c (ffffffff81887e75)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce44b)
Location: include/linux/irqdomain.h:420
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108fdf5)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
```
```
In kernel/irq/generic-chip.c (ffffffff81168f87)
Location: include/linux/irqdomain.h:434
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff8116bebf)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In kernel/irq/irq_sim.c (ffffffff8116c2d2)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/msi.c (ffffffff8116e5fe)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179ae00)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a1019)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff817a55b4)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff817b30ab)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b22e5)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c2b13)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
```
In drivers/mfd/twl6030-irq.c (ffffffff819c718a)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc0a4)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cee79)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
```
```
In drivers/mfd/max8998-irq.c (ffffffff819cfe98)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
```
In drivers/mfd/tps6586x.c (ffffffff819d0ee5)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2feef)
Location: include/linux/irqdomain.h:434
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a4db5)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
```
```
In kernel/irq/generic-chip.c (ffffffff8119d807)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
```
```
In kernel/irq/irqdomain.c (ffffffff811a0763)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In kernel/irq/irq_sim.c (ffffffff811a125a)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/msi.c (ffffffff811a3bee)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b0bb8)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b713a)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
```
```
In drivers/gpio/gpiolib.c (ffffffff818bd199)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff818cd0cb)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b27385)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b38d43)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81b3dee6)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b43e04)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b47c49)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b48e6c)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a2fa)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc448f)
Location: include/linux/irqdomain.h:422
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a7e95)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
```
```
In kernel/irq/generic-chip.c (ffffffff811af6b7)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
```
```
In kernel/irq/irqdomain.c (ffffffff811b25d4)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In kernel/irq/irq_sim.c (ffffffff811b306a)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/msi.c (ffffffff811b5bee)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f3bb8)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/gpio/gpiolib.c (ffffffff81900467)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff8191012b)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b76c40)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8c1ac)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81b91376)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b971b4)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b017)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b9c2c8)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d769)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c0ff)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810aeef5)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
```
```
In kernel/irq/generic-chip.c (ffffffff811bf1e7)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811c23c4)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In kernel/irq/irq_sim.c (ffffffff811c2e8a)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
```
```
In kernel/irq/msi.c (ffffffff811c5a6e)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193b3e8)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
```
```
In drivers/gpio/gpiolib.c (ffffffff81947d17)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81957ffb)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcaa10)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81be00ac)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
```
In drivers/mfd/twl6030-irq.c (ffffffff81be5316)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb184)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
```
```
In drivers/mfd/max8997-irq.c (ffffffff81beefd7)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
```
```
In drivers/mfd/max8998-irq.c (ffffffff81bf02b8)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1759)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de1fbf)
Location: include/linux/irqdomain.h:425
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
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
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101831a8)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_to_irq
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_find_irq
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_to_irq
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/acpi/irq.c:acpi_unregister_gsi
  - drivers/acpi/irq.c:acpi_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffff8000101831a8-ffff80001018326c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d24f0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_handler
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_request_free
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_find_irq
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_to_irq
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_to_irq
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
  - drivers/soc/dove/pmu.c:pmu_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/tps65217.c:tps65217_remove
  - drivers/mfd/tps65217.c:tps65217_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
  - drivers/memory/omap-gpmc.c:gpmc_remove
  - drivers/memory/omap-gpmc.c:gpmc_handle_irq
```
**Symbols:**

```
c03d24f0-c03d25ac: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de1f0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_get_irq
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_get_irq
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_get_irq
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
c0000000001de1f0-c0000000001de320: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a59a)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-sifive-plic.c:plic_handle_irq
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffe00011a59a-ffffffe00011a64a: irq_find_mapping (STB_GLOBAL)
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
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811161d0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
**Symbols:**

```
ffffffff811161d0-ffffffff8111626c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106ec0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
**Symbols:**

```
ffffffff81106ec0-ffffffff81106f5c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811140c0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811140c0-ffffffff8111415c: irq_find_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f6e0)
Location: kernel/irq/irqdomain.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8111f6e0-ffffffff8111f78d: irq_find_mapping (STB_GLOBAL)
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
