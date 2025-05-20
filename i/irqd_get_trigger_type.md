# Function: <code>irqd_get_trigger_type</code>

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
In kernel/irq/manage.c (ffffffff810dc5a4)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/irqdomain.c (ffffffff810e1526)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81422c75)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e5bc)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815885c1)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/mfd/palmas.c (ffffffff81594da8)
Location: include/linux/irq.h:238
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
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
In kernel/irq/manage.c (ffffffff810e2840)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810e3f44)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff810e7090)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146be77)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474826)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/acpi/pci_link.c (ffffffff814d51ec)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_irq_get_penalty
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d392c)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dd8ee)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff815e9c48)
Location: include/linux/irq.h:246
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
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
In kernel/irq/manage.c (ffffffff810e9160)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810ea4a0)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff810eda80)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489a9a)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148c247)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e513)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149635a)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff81600676)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a57e)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81616a58)
Location: include/linux/irq.h:248
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
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
In kernel/irq/manage.c (ffffffff810e8660)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810e8fdc)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff810ed446)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814932a8)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81495ad7)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814980f3)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149ff46)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff816144f2)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161e67c)
Location: include/linux/irq.h:262
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff8162a96b)
Location: include/linux/irq.h:262
Inline: True
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
In kernel/irq/manage.c (ffffffff810f0a30)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810f143c)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff810f5e49)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cf538)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d1dd7)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d435e)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de9e6)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167cb98)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81686ebc)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff816932ab)
Location: include/linux/irq.h:272
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787c97)
Location: include/linux/irq.h:272
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff810f8df0)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff810f987c)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff810fe1f1)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500742)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81502e4e)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505375)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150dcc4)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8603)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c2fee)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff816cf3d4)
Location: include/linux/irq.h:267
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8d93)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81104590)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8110502c)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff811099c1)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515197)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81517a47)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81519d55)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff815239c4)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d9824)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e43de)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff816f09f4)
Location: include/linux/irq.h:268
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f0433)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff8110d090)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8110e30f)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81112fb0)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543357)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81545c39)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81547eb5)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81551e8b)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714f7c)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171da6f)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff8172a0f9)
Location: include/linux/irq.h:268
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183084a)
Location: include/linux/irq.h:268
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81119470)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8111a5cf)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff8111f241)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564267)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81566b60)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81568dd5)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8157350b)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff8173928c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81741d3f)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff8174e2f9)
Location: include/linux/irq.h:271
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8186217a)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81124d10)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8112664f)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff8112b781)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606797)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816091ab)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160b005)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff816173ab)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f6b0c)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ff85f)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff8180c917)
Location: include/linux/irq.h:277
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935926)
Location: include/linux/irq.h:277
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81120b70)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8112228f)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81127241)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d8bb)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162f745)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e862)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/arizona-irq.c (ffffffff81809840)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81810aff)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81c1542e)
Location: include/linux/irq.h:282
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c9a5)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81120e40)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8112260f)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81127501)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8161152b)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816133e5)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81622272)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee425)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f527f)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81c0718a)
Location: include/linux/irq.h:282
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8192026c)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff811413c0)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81142bbf)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81147a6d)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816807db)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682655)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff816919c1)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e35d)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81d0a792)
Location: include/linux/irq.h:284
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2f0c)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81164d95)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81166867)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff8116befe)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c396)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179ee45)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b0ee7)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c685a)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81ed2c4a)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b2335f)
Location: include/linux/irq.h:284
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff81198bc5)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8119ab17)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff811a08c7)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2da6)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b5ad5)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff818caa70)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d34d)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81b4bdd3)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5c34)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff811aa8a5)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811ac877)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff811b273a)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f5df6)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f8b95)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190db65)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b907d6)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81b9f223)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d2c0)
Location: include/linux/irq.h:289
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff811ba425)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811bc477)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff811c252a)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193e569)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81940835)
Location: include/linux/irq.h:286
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff819558c5)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4746)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff81bf3380)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2ffb)
Location: include/linux/irq.h:286
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In virt/kvm/arm/arch_timer.c (ffff8000100ed9b4)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
```
```
In kernel/irq/manage.c (ffff80001017bfd0)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffff80001017dc4c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffff800010184d9c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e890)
Location: include/linux/irq.h:271
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010694108)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a1d6c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106abfa8)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ae0c4)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cb418)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cd958)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:gpio_irq_enable
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d18e8)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/mfd/stmpe.c (ffff80001092fa70)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (ffff800010934020)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d4ac)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffff80001094d194)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/as3722.c (ffff80001094f4a8)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc2d0)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b672dc)
Location: include/linux/irq.h:271
Inline: True
```
```
In drivers/of/irq.c (ffff800010b75174)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
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
In kernel/irq/manage.c (c03cd034)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (c03ce420)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (c03d3e54)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (c0834bb8)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c08457c4)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084f1dc)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0851d90)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_unmask
```
```
In drivers/gpio/gpio-mvebu.c (c086b09c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/gpio/gpio-omap.c (c086e2c0)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
```
```
In drivers/mfd/stmpe.c (c0a1110c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (c0a16eb0)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0a25f04)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (c0a372dc)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/as3722.c (c0a39534)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b3e0)
Location: include/linux/irq.h:271
Inline: True
```
```
In drivers/of/irq.c (c0c57630)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
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
In kernel/irq/manage.c (c0000000001d6b10)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (c0000000001d8548)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (c0000000001df29c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (c000000000830f18)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/mfd/stmpe.c (c0000000009cf884)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4f04)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5314)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (c0000000009f9550)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/as3722.c (c0000000009fbe84)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/of/irq.c (c000000000c5261c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
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
In kernel/irq/manage.c (ffffffe000115806)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffe00011684a)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffe00011bc04)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e6e8)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/mfd/stmpe.c (ffffffe0005a63e8)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9c82)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b176e)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffe0005be354)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/as3722.c (ffffffe0005bfd34)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/of/irq.c (ffffffe0007289e0)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
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
In kernel/irq/manage.c (ffffffff81111a50)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81112baf)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81117821)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155c857)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155e030)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568ccb)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcfec)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In kernel/irq/manage.c (ffffffff81102780)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff811038cf)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81108511)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154d170)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f3e5)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559b1b)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0dfc)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In kernel/irq/manage.c (ffffffff8110f940)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff81110a9f)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81115711)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558597)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155ae90)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155d105)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8156783b)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c74c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817351ff)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff817417b9)
Location: include/linux/irq.h:271
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185630a)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In kernel/irq/manage.c (ffffffff8111ae70)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__irq_set_trigger
```
```
In kernel/irq/chip.c (ffffffff8111c01f)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In kernel/irq/irqdomain.c (ffffffff81120d41)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572427)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574d20)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81577025)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8158175b)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/arizona-irq.c (ffffffff81747b8c)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8175063f)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
  - drivers/mfd/twl4030-irq.c:twl4030_sih_set_type
```
```
In drivers/mfd/palmas.c (ffffffff8175cbf9)
Location: include/linux/irq.h:271
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187143a)
Location: include/linux/irq.h:271
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
</details>
</li>
</ul>

## Differences
