# Function: <code>device_property_read_bool</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff816d1a21)
Location: include/linux/property.h:87
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/usb/dwc2/params.c (ffffffff816b15db)
Location: include/linux/property.h:87
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_param
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff816ff901)
Location: include/linux/property.h:87
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81715243)
Location: include/linux/property.h:102
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff817757ef)
Location: include/linux/property.h:102
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/mfd/da9052-core.c (ffffffff8168bcfc)
Location: include/linux/property.h:108
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81786463)
Location: include/linux/property.h:108
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff817ebaff)
Location: include/linux/property.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff816301ba)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff816c7d89)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817c7537)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81834ccf)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff8164e36a)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff816e9249)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817eeb96)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81860c7f)
Location: include/linux/property.h:116
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff81682eca)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81722a64)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8182f796)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff818a49bf)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c2e72)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
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
In drivers/tty/serial/serial_core.c (ffffffff816a556a)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81746d04)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff818610c6)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff818d6e3b)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff81757bb2)
Location: include/linux/property.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81804a04)
Location: include/linux/property.h:123
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8193437a)
Location: include/linux/property.h:123
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff819a9795)
Location: include/linux/property.h:123
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff81772c70)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81815434)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff818e212b)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff818e25e8)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8193b3fa)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff819ac385)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff817566e7)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff817f9b14)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff818c543b)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff818c5928)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
```
```
In drivers/input/touchscreen.c (ffffffff819187a9)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81990815)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff817d9e17)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81882fc4)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff8195d21e)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff8195d8a8)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
```
```
In drivers/input/touchscreen.c (ffffffff819baab9)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81a3c125)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff8191889f)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff819263e4)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
```
```
In drivers/mfd/da9052-core.c (ffffffff819cb98f)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ab718e)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff81ab799b)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
```
```
In drivers/input/touchscreen.c (ffffffff81b1a86d)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81ba917a)
Location: include/linux/property.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff81a74303)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81a831f6)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
```
```
In drivers/mfd/da9052-core.c (ffffffff81b43509)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff81c3fc4e)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff81c4058b)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
```
```
In drivers/input/touchscreen.c (ffffffff81cac5ad)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81d4be6e)
Location: include/linux/property.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff81abe983)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81ace856)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
```
```
In drivers/mfd/da9052-core.c (ffffffff81b96879)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ca71be)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff81ca7b5b)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
```
```
In drivers/input/touchscreen.c (ffffffff81d13b8d)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81db670e)
Location: include/linux/property.h:157
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/gpio/gpio-mmio.c (ffffffff8195763f)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11731)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81b21916)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
```
```
In drivers/mfd/da9052-core.c (ffffffff81bea849)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/usb/dwc2/drd.c (ffffffff81d5be0e)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
```
In drivers/usb/dwc2/params.c (ffffffff81d5c7eb)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
```
```
In drivers/input/touchscreen.c (ffffffff81dc97bd)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff81e6ebae)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffff80001087d8ac)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff80001089176c)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7e74)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/mfd/da9052-core.c (ffff80001094375c)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc234)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffff800010aa39f4)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/power/reset/gpio-poweroff.c (ffff800010ac96ac)
Location: include/linux/property.h:118
Inline: True
```
```
In drivers/mmc/core/host.c (ffff800010b30ed0)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (c097f4ac)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/iommu/rockchip-iommu.c (c09c5900)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/mfd/da9052-core.c (c0a2c820)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (c0b83290)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/power/reset/gpio-poweroff.c (c0baa368)
Location: include/linux/property.h:118
Inline: True
```
```
In drivers/mmc/core/host.c (c0c0bc34)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2cd54)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
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
In drivers/tty/serial/serial_core.c (c0000000009248a0)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (c0000000009ecc04)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (c000000000b846a4)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/power/reset/gpio-poweroff.c (c000000000bab4ac)
Location: include/linux/property.h:118
Inline: True
```
```
In drivers/mmc/core/host.c (c000000000c2aa74)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffe00054c2d8)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffe0005b6358)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffe0006b109c)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/power/reset/gpio-poweroff.c (ffffffe0006c77a2)
Location: include/linux/property.h:118
Inline: True
```
```
In drivers/mmc/core/host.c (ffffffe00070995c)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff8166afca)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81703d74)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/mmc/core/host.c (ffffffff8187a7fb)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff8164a13a)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff816d7b74)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
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
In drivers/tty/serial/serial_core.c (ffffffff816993aa)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff8173a1c4)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81855256)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff818cbc9b)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
In drivers/tty/serial/serial_core.c (ffffffff816b3a5a)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
```
In drivers/mfd/da9052-core.c (ffffffff81755604)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81870386)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/mmc/core/host.c (ffffffff818e87bb)
Location: include/linux/property.h:118
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
</details>
</li>
</ul>

## Differences
