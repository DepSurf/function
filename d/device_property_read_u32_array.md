# Function: <code>device_property_read_u32_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551ec0)
Location: drivers/base/property.c:295
Inline: False
Direct callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
**Symbols:**

```
ffffffff81551ec0-ffffffff81551ed7: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3a70)
Location: drivers/base/property.c:301
Inline: False
Direct callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff815a3a70-ffffffff815a3a87: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d2180)
Location: drivers/base/property.c:301
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_set_parameters
  - drivers/usb/dwc2/params.c:dwc2_set_parameters
  - drivers/usb/dwc2/params.c:dwc2_set_param
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff815d2180-ffffffff815d2197: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e62c0)
Location: drivers/base/property.c:333
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff815e62c0-ffffffff815e62e2: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d630)
Location: drivers/base/property.c:342
Inline: False
Direct callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff8164d630-ffffffff8164d652: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688830)
Location: drivers/base/property.c:403
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff81688830-ffffffff81688852: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8520)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816a8520-ffffffff816a8542: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1dc0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
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
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
```
**Symbols:**

```
ffffffff816e1dc0-ffffffff816e1de2: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705f70)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff81705f70-ffffffff81705f92: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c05e0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/keyboard/atkbd.c:atkbd_parse_fwnode_data
  - drivers/input/keyboard/atkbd.c:atkbd_parse_fwnode_data
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/rtc/class.c:rtc_device_get_offset
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff817c05e0-ffffffff817c0602: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d54a0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/keyboard/atkbd.c:atkbd_parse_fwnode_data
  - drivers/input/keyboard/atkbd.c:atkbd_parse_fwnode_data
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/rtc/class.c:rtc_device_get_offset
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff817d54a0-ffffffff817d54c2: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8ee0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
  - drivers/mmc/core/host.c:mmc_of_parse_clk_phase
```
**Symbols:**

```
ffffffff817b8ee0-ffffffff817b8f02: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842b40)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse_timing_phase
```
**Symbols:**

```
ffffffff81842b40-ffffffff81842b62: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819863d0)
Location: drivers/base/property.c:138
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse_timing_phase
```
**Symbols:**

```
ffffffff819863d0-ffffffff81986401: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4a00)
Location: drivers/base/property.c:145
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse_timing_phase
```
**Symbols:**

```
ffffffff81af4a00-ffffffff81af4a31: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_property_read_u32_array(const struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42c10)
Location: drivers/base/property.c:149
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse_timing_phase
```
**Symbols:**

```
ffffffff81b42c10-ffffffff81b42c41: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_property_read_u32_array(const struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9aae0)
Location: drivers/base/property.c:149
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_get_ngpios
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/iommu/iommu.c:iommu_init_device
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse_timing_phase
```
**Symbols:**

```
ffffffff81b9aae0-ffffffff81b9ab11: device_property_read_u32_array (STB_GLOBAL)
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
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2c70)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
```
**Symbols:**

```
ffff8000108f2c70-ffff8000108f2cd0: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df850)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_get_property
```
**Symbols:**

```
c09df850-c09df890: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c8e0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
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
c00000000098c8e0-c00000000098c920: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584698)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffe000584698-ffffffe0005846ea: device_property_read_u32_array (STB_GLOBAL)
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
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb6c0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816cb6c0-ffffffff816cb6e2: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a69f0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
```
**Symbols:**

```
ffffffff816a69f0-ffffffff816a6a12: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9c30)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816f9c30-ffffffff816f9c52: device_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_property_read_u32_array(struct device *dev, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817144d0)
Location: drivers/base/property.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff817144d0-ffffffff817144f2: device_property_read_u32_array (STB_GLOBAL)
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
