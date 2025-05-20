# Function: <code>irq_get_trigger_type</code>

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
In kernel/irq/irqdomain.c (ffffffff810e1516)
Location: include/linux/irq.h:652
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8158885f)
Location: include/linux/irq.h:652
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
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
In kernel/irq/irqdomain.c (ffffffff810e707f)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8147481a)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/acpi/pci_link.c (ffffffff814d51db)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_irq_get_penalty
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dd8e4)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
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
In kernel/irq/irqdomain.c (ffffffff810eda6f)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489a82)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149634e)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a574)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
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
In kernel/irq/irqdomain.c (ffffffff810ed438)
Location: include/linux/irq.h:748
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493292)
Location: include/linux/irq.h:748
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149ff3a)
Location: include/linux/irq.h:748
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161e672)
Location: include/linux/irq.h:748
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
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
In kernel/irq/irqdomain.c (ffffffff810f5e3b)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cf522)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de9da)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81686eb2)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787c80)
Location: include/linux/irq.h:777
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
In kernel/irq/irqdomain.c (ffffffff810fe1e3)
Location: include/linux/irq.h:779
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500738)
Location: include/linux/irq.h:779
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150dcb8)
Location: include/linux/irq.h:779
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c2fdf)
Location: include/linux/irq.h:779
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8d7b)
Location: include/linux/irq.h:779
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
In kernel/irq/irqdomain.c (ffffffff811099b3)
Location: include/linux/irq.h:780
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515189)
Location: include/linux/irq.h:780
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff815239b8)
Location: include/linux/irq.h:780
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e43cf)
Location: include/linux/irq.h:780
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f041b)
Location: include/linux/irq.h:780
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
In kernel/irq/irqdomain.c (ffffffff81112fa2)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543349)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81551e7e)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171da5f)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830834)
Location: include/linux/irq.h:793
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
In kernel/irq/irqdomain.c (ffffffff8111f233)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564259)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff815734fe)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81741d2f)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81862164)
Location: include/linux/irq.h:811
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
In kernel/irq/irqdomain.c (ffffffff8112b773)
Location: include/linux/irq.h:841
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606789)
Location: include/linux/irq.h:841
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8161739e)
Location: include/linux/irq.h:841
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ff84f)
Location: include/linux/irq.h:841
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935910)
Location: include/linux/irq.h:841
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
In kernel/irq/irqdomain.c (ffffffff81127233)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e856)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81810aef)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c98f)
Location: include/linux/irq.h:854
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
In kernel/irq/irqdomain.c (ffffffff811274f3)
Location: include/linux/irq.h:856
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81622266)
Location: include/linux/irq.h:856
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f526f)
Location: include/linux/irq.h:856
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81920256)
Location: include/linux/irq.h:856
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
In kernel/irq/irqdomain.c (ffffffff81147a5e)
Location: include/linux/irq.h:858
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff816919b5)
Location: include/linux/irq.h:858
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e34c)
Location: include/linux/irq.h:858
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2ef6)
Location: include/linux/irq.h:858
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
In kernel/irq/irqdomain.c (ffffffff8116beef)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b0eda)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6849)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23348)
Location: include/linux/irq.h:862
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
In kernel/irq/irqdomain.c (ffffffff811a08b8)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff818caa63)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d33d)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5c1c)
Location: include/linux/irq.h:864
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
In kernel/irq/irqdomain.c (ffffffff811b272b)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190db59)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b907c3)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d2a9)
Location: include/linux/irq.h:877
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
In kernel/irq/irqdomain.c (ffffffff811c251b)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff819558b9)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4733)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2fe3)
Location: include/linux/irq.h:859
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
In virt/kvm/arm/arch_timer.c (ffff8000100ed9ac)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
```
```
In kernel/irq/irqdomain.c (ffff800010184d90)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff8000106940fc)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106abfa0)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cb40c)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d18e0)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/mfd/stmpe.c (ffff80001092fa68)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d49c)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b672d0)
Location: include/linux/irq.h:811
Inline: True
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
In kernel/irq/irqdomain.c (c03d3e4c)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (c0834ba8)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpio-mvebu.c (c086b090)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/mfd/stmpe.c (c0a11104)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl4030-irq.c (c0a25ef0)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b3d0)
Location: include/linux/irq.h:811
Inline: True
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
In kernel/irq/irqdomain.c (c0000000001df288)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (c000000000830f04)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/mfd/stmpe.c (c0000000009cf870)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e52f8)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
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
In kernel/irq/irqdomain.c (ffffffe00011bbf6)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e6dc)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/mfd/stmpe.c (ffffffe0005a63dc)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1758)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
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
In kernel/irq/irqdomain.c (ffffffff81117813)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155c849)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568cbe)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
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
In kernel/irq/irqdomain.c (ffffffff81108503)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559b0e)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
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
In kernel/irq/irqdomain.c (ffffffff81115703)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558589)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8156782e)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817351ef)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818562f4)
Location: include/linux/irq.h:811
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
In kernel/irq/irqdomain.c (ffffffff81120d33)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572419)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8158174e)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8175062f)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81871424)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
</details>
</li>
</ul>

## Differences
