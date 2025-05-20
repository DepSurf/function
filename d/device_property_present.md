# Function: <code>device_property_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551570)
Location: drivers/base/property.c:193
Inline: False
```
**Symbols:**

```
ffffffff81551570-ffffffff81551587: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2e30)
Location: drivers/base/property.c:198
Inline: False
Direct callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
**Symbols:**

```
ffffffff815a2e30-ffffffff815a2e47: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1540)
Location: drivers/base/property.c:198
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_set_param
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
**Symbols:**

```
ffffffff815d1540-ffffffff815d1557: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6bd0)
Location: drivers/base/property.c:241
Inline: False
Direct callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff815e6bd0-ffffffff815e6be7: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164e010)
Location: drivers/base/property.c:249
Inline: False
Direct callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff8164e010-ffffffff8164e027: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689760)
Location: drivers/base/property.c:310
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff81689760-ffffffff81689777: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a9020)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff816a9020-ffffffff816a9037: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e25f0)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
```
**Symbols:**

```
ffffffff816e25f0-ffffffff816e2607: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817067a0)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff817067a0-ffffffff817067b7: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0440)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff817c0440-ffffffff817c0457: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5300)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff817d5300-ffffffff817d5317: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8d40)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff817b8d40-ffffffff817b8d57: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818429a0)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff818429a0-ffffffff818429b7: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819861a0)
Location: drivers/base/property.c:34
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff819861a0-ffffffff819861bf: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4760)
Location: drivers/base/property.c:41
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81af4760-ffffffff81af477f: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool device_property_present(const struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42970)
Location: drivers/base/property.c:43
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81b42970-ffffffff81b4298f: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool device_property_present(const struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9a840)
Location: drivers/base/property.c:43
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/params.c:dwc2_set_stm32mp15_hsotg_params
  - drivers/usb/dwc2/params.c:dwc2_set_x2000_params
  - drivers/usb/dwc2/params.c:dwc2_set_x1600_params
  - drivers/usb/dwc2/params.c:dwc2_set_jz4775_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81b9a840-ffffffff81b9a85f: device_property_present (STB_GLOBAL)
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
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3788)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffff8000108f3788-ffff8000108f37dc: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09e008c)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
```
**Symbols:**

```
c09e008c-c09e00b8: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d5d0)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
c00000000098d5d0-c00000000098d608: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584e50)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffe000584e50-ffffffe000584e90: device_property_present (STB_GLOBAL)
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
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbef0)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff816cbef0-ffffffff816cbf07: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a7220)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
```
**Symbols:**

```
ffffffff816a7220-ffffffff816a7237: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa460)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff816fa460-ffffffff816fa477: device_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool device_property_present(struct device *dev, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714d00)
Location: drivers/base/property.c:35
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
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
**Symbols:**

```
ffffffff81714d00-ffffffff81714d17: device_property_present (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
