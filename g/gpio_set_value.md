# Function: <code>gpio_set_value</code>

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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
```
```
In drivers/mfd/twl6040.c (ffffffff8158a2de)
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff815948bc)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core.c (ffffffff81679323)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
```
```
In drivers/mfd/twl6040.c (ffffffff815df42f)
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff815e992c)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core.c (ffffffff816da7e3)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
```
```
In drivers/mfd/twl6040.c (ffffffff8160c0cf)
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8161673c)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core.c (ffffffff8170acd3)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816201e2)
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8162a64c)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:58
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f5d3)
Location: include/linux/gpio.h:58
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
Location: include/linux/gpio.h:59
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81688a22)
Location: include/linux/gpio.h:59
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81692f7c)
Location: include/linux/gpio.h:59
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
Location: include/linux/gpio.h:59
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790533)
Location: include/linux/gpio.h:59
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816c4b8f)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff816cedec)
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816e5f7f)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff816f06ac)
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8171f582)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81729d19)
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81743852)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174df49)
Location: include/linux/gpio.h:69
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3e66)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81800ecc)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180c189)
Location: include/linux/gpio.h:69
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff81807ac6)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81811e1c)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181b4c9)
Location: include/linux/gpio.h:69
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec698)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817f6834)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff817febf9)
Location: include/linux/gpio.h:69
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff81879278)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187fb39)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81888b7e)
Location: include/linux/gpio.h:69
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/htc-i2cpld.c (ffffffff819c182a)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c811e)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff819d1cfc)
Location: include/linux/gpio.h:69
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/aat2870-core.c (ffffffff81b4b80c)
Location: include/linux/gpio.h:69
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/aat2870-core.c (ffffffff81b9ec5c)
Location: include/linux/gpio.h:106
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
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/aat2870-core.c (ffffffff81bf2dbc)
Location: include/linux/gpio.h:106
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093fb08)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c638)
Location: include/linux/gpio.h:69
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
In <code>armhf</code>: Absent ⚠️
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (c0000000009e7a44)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (c0000000009f89dc)
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffe0005b369c)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd806)
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81736d12)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff81741409)
Location: include/linux/gpio.h:69
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
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81752152)
Location: include/linux/gpio.h:69
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c849)
Location: include/linux/gpio.h:69
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
