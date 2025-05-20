# Function: <code>irq_create_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0990)
Location: kernel/irq/irqdomain.c:461
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:_gpiochip_irqchip_add
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
**Symbols:**

```
ffffffff810e0990-ffffffff810e0b0e: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6840)
Location: kernel/irq/irqdomain.c:457
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:_gpiochip_irqchip_add
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
**Symbols:**

```
ffffffff810e6840-ffffffff810e69b8: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed230)
Location: kernel/irq/irqdomain.c:480
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core.c:i2c_device_probe
```
**Symbols:**

```
ffffffff810ed230-ffffffff810ed3a8: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecca0)
Location: kernel/irq/irqdomain.c:618
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
**Symbols:**

```
ffffffff810ecca0-ffffffff810ece21: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f56f0)
Location: kernel/irq/irqdomain.c:632
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
**Symbols:**

```
ffffffff810f56f0-ffffffff810f5861: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fdaa0)
Location: kernel/irq/irqdomain.c:634
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff810fdaa0-ffffffff810fdc15: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109270)
Location: kernel/irq/irqdomain.c:634
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81109270-ffffffff811093e5: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112870)
Location: kernel/irq/irqdomain.c:648
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81112870-ffffffff811129e5: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111eb00)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff8111eb00-ffffffff8111ec75: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112ab10)
Location: kernel/irq/irqdomain.c:635
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff8112ab10-ffffffff8112ac75: irq_create_mapping (STB_GLOBAL)
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
In kernel/irq/irqdomain.c (ffffffff81127348)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81636551)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f92b4)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/arizona-irq.c (ffffffff818096b5)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8180daef)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff81812d07)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff8181a7c5)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81947b5c)
Location: include/linux/irqdomain.h:397
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
In kernel/irq/irqdomain.c (ffffffff81127608)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8161933f)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd524)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee298)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff817f22cf)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff817f7428)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff817fdee5)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192b47c)
Location: include/linux/irqdomain.h:402
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
In kernel/irq/irqdomain.c (ffffffff81147b74)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8168860f)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81868fd4)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8187af1f)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff81880746)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff81887bf5)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce65c)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
In kernel/irq/irqdomain.c (ffffffff8116bfbe)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff817a5902)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1c14)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff819c3753)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff819c8e08)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff819d0c05)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b3032c)
Location: include/linux/irqdomain.h:413
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
In drivers/gpio/gpiolib.c (ffffffff818bd599)
Location: include/linux/irqdomain.h:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26b84)
Location: include/linux/irqdomain.h:401
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81b39c23)
Location: include/linux/irqdomain.h:401
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff81b40129)
Location: include/linux/irqdomain.h:401
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff81b49fe5)
Location: include/linux/irqdomain.h:401
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4a9f)
Location: include/linux/irqdomain.h:401
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
In drivers/gpio/gpiolib.c (ffffffff81901642)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b769f4)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81b8d083)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff81b934a2)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d445)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c3df)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
In drivers/gpio/gpiolib.c (ffffffff81948f42)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bca7c4)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81be0fb3)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
```
```
In drivers/mfd/mfd-core.c (ffffffff81be7442)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1435)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de22af)
Location: include/linux/irqdomain.h:404
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
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
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101844c8)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_to_irq
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpio-davinci.c:gpio_to_irq_banked
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_to_irq
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_to_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffff8000101844c8-ffff8000101846e8: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d35ec)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_to_irq
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_to_irq
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_to_irq
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_to_irq
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-tegra.c:tegra_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/memory/omap-gpmc.c:gpmc_get_client_irq
```
**Symbols:**

```
c03d35ec-c03d37e8: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dee50)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/sysdev/mpic.c:mpic_request_ipis
  - arch/powerpc/sysdev/mpic_u3msi.c:u3msi_setup_msi_irqs
  - arch/powerpc/sysdev/xics/xics-common.c:xics_smp_probe
  - arch/powerpc/sysdev/xive/common.c:xive_smp_probe
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_request
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
c0000000001dee50-c0000000001df110: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b4d4)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffe00011b4d4-ffffffe00011b68c: irq_create_mapping (STB_GLOBAL)
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
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811170e0)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff811170e0-ffffffff81117255: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107dd0)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81107dd0-ffffffff81107f45: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114fd0)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81114fd0-ffffffff81115145: irq_create_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain *domain, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120600)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81120600-ffffffff81120775: irq_create_mapping (STB_GLOBAL)
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
