# Function: <code>__gpio_set_value</code>

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
In drivers/mfd/htc-i2cpld.c (ffffffff8157be69)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
```
```
In drivers/mfd/twl6040.c (ffffffff8158a2de)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff815948bc)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
```
```
In drivers/spi/spi.c (ffffffff815e6974)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core.c (ffffffff81679323)
Location: include/asm-generic/gpio.h:97
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
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
In drivers/mfd/htc-i2cpld.c (ffffffff815d0f0e)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
```
```
In drivers/mfd/twl6040.c (ffffffff815df42f)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff815e992c)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/spi/spi.c (ffffffff81644d44)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core.c (ffffffff816da7e3)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
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
In drivers/mfd/htc-i2cpld.c (ffffffff815fdae6)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
```
```
In drivers/mfd/twl6040.c (ffffffff8160c0cf)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8161673c)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/spi/spi.c (ffffffff81675e28)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core.c (ffffffff8170acd3)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
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
In drivers/mfd/htc-i2cpld.c (ffffffff816118f0)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816201e2)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8162a64c)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/spi/spi.c (ffffffff8168a578)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f5d3)
Location: include/asm-generic/gpio.h:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
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
In drivers/mfd/htc-i2cpld.c (ffffffff8167a17b)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81688a22)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81692f7c)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/spi/spi.c (ffffffff816f3d8b)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790533)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
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
In drivers/mfd/htc-i2cpld.c (ffffffff816b5c22)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816c4b8f)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff816cedec)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/spi/spi.c (ffffffff817307cb)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/mfd/htc-i2cpld.c (ffffffff816d6e82)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816e5f7f)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff816f06ac)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/spi/spi.c (ffffffff81752eac)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/mfd/htc-i2cpld.c (ffffffff817125b4)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8171f582)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81729d19)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
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
In drivers/mfd/htc-i2cpld.c (ffffffff817368b4)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81743852)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174df49)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __gpio_set_value(unsigned int gpio, int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3d50)
Location: include/asm-generic/gpio.h:100
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81800ecc)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180c189)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff817f3d50-ffffffff817f3d6f: __gpio_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __gpio_set_value(unsigned int gpio, int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff818079b0)
Location: include/asm-generic/gpio.h:100
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81811e1c)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181b4c9)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff818079b0-ffffffff818079cf: __gpio_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __gpio_set_value(unsigned int gpio, int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec580)
Location: include/asm-generic/gpio.h:100
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817f6834)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff817febf9)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff817ec580-ffffffff817ec59f: __gpio_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __gpio_set_value(unsigned int gpio, int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff81879160)
Location: include/asm-generic/gpio.h:100
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187fb39)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81888b7e)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81879160-ffffffff8187917f: __gpio_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __gpio_set_value(unsigned int gpio, int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff819c16f0)
Location: include/asm-generic/gpio.h:100
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c811e)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff819d1cfc)
Location: include/asm-generic/gpio.h:100
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff819c16f0-ffffffff819c1716: __gpio_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/aat2870-core.c (ffffffff81b4b80c)
Location: include/asm-generic/gpio.h:78
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/mfd/htc-i2cpld.c (ffff80001092e254)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093fb08)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c638)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
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
In arch/arm/mach-omap2/pdata-quirks.c (c1518b00)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init
```
```
In drivers/tty/serial/omap-serial.c (c099ee50)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
```
```
In drivers/mfd/htc-i2cpld.c (c0a0fcd8)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (c0a29234)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (c0a36a80)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
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
In drivers/mfd/htc-i2cpld.c (c0000000009cdc5c)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (c0000000009e7a44)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (c0000000009f89dc)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
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
In drivers/mfd/htc-i2cpld.c (ffffffe0005a5020)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffe0005b369c)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd806)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff81729d74)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81736d12)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81741409)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
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
In drivers/mfd/htc-i2cpld.c (ffffffff817451b4)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81752152)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c849)
Location: include/asm-generic/gpio.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
