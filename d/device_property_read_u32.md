# Function: <code>device_property_read_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8167145b)
Location: include/linux/property.h:102
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff816d178f)
Location: include/linux/property.h:105
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/i2c/i2c-core.c (ffffffff816daa66)
Location: include/linux/property.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
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
In drivers/usb/dwc2/params.c (ffffffff816b15b7)
Location: include/linux/property.h:105
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_param
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff816ff66f)
Location: include/linux/property.h:105
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ad56)
Location: include/linux/property.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core.c:i2c_parse_fw_timings
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
In drivers/usb/dwc2/params.c (ffffffff816c70e0)
Location: include/linux/property.h:120
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8171500a)
Location: include/linux/property.h:120
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f656)
Location: include/linux/property.h:120
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817278ec)
Location: include/linux/property.h:120
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/host.c (ffffffff81775789)
Location: include/linux/property.h:120
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff81733533)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8178622a)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817905b6)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798ec6)
Location: include/linux/property.h:126
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/host.c (ffffffff817eba99)
Location: include/linux/property.h:126
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff8177336e)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817c730a)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff817cb5e0)
Location: include/linux/property.h:134
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d31d5)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dbd27)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/host.c (ffffffff81834c69)
Location: include/linux/property.h:134
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff8179858a)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817ee8dd)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff817f2c4b)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/rtc/class.c:__rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fa316)
Location: include/linux/property.h:134
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/mmc/core/host.c (ffffffff81860c19)
Location: include/linux/property.h:134
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff817d71b1)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8182f4dd)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff81833907)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183b046)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/mmc/core/host.c (ffffffff818a4969)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c2e66)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff81808041)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81860e0d)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff8186529a)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186c9d6)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/mmc/core/host.c (ffffffff818d6de5)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff818d8ba3)
Location: include/linux/property.h:141
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff819340de)
Location: include/linux/property.h:141
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff81938a8e)
Location: include/linux/property.h:141
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_device_get_offset
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819406d5)
Location: include/linux/property.h:141
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
```
```
In drivers/mmc/core/host.c (ffffffff819a973f)
Location: include/linux/property.h:141
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff818e30a3)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8193b15e)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff8193ec6e)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_device_get_offset
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946ac6)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
```
```
In drivers/mmc/core/host.c (ffffffff819ac32f)
Location: include/linux/property.h:144
Inline: True
Inline callers:
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
In drivers/dma/lgm/lgm-dma.c (ffffffff8170972b)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/params.c (ffffffff818c642b)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen.c (ffffffff8191850e)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff819224c8)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192a3c6)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
```
```
In drivers/mmc/core/host.c (ffffffff819907bf)
Location: include/linux/property.h:144
Inline: True
Inline callers:
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
In drivers/dma/lgm/lgm-dma.c (ffffffff817850e1)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff817e00b1)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec389)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/usb/dwc2/params.c (ffffffff8195e549)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen.c (ffffffff819ba81e)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff819c547b)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cd566)
Location: include/linux/property.h:144
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
```
```
In drivers/mmc/core/host.c (ffffffff81a3c0cf)
Location: include/linux/property.h:144
Inline: True
Inline callers:
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
In drivers/gpio/gpiolib.c (ffffffff817a909d)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbcc2)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8191ed7f)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8192af12)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/usb/dwc2/params.c (ffffffff81ab88a1)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen.c (ffffffff81b1a5a5)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff81b25f8f)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2f676)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
```
```
In drivers/mmc/core/host.c (ffffffff81ba9124)
Location: include/linux/property.h:150
Inline: True
Inline callers:
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
In drivers/gpio/gpiolib.c (ffffffff818c1a00)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a8aa)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81a7b138)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81a896a2)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/iommu/iommu.c (ffffffff81ad1abd)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
```
In drivers/usb/dwc2/params.c (ffffffff81c41b11)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen.c (ffffffff81cac2e5)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff81cb9566)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc3596)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_timing
```
```
In drivers/mmc/core/host.c (ffffffff81d4be04)
Location: include/linux/property.h:164
Inline: True
Inline callers:
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
In drivers/gpio/gpiolib.c (ffffffff8190495b)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53731)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81ac69a8)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4e71)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/iommu/iommu.c (ffffffff81b1f58d)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
```
In drivers/usb/dwc2/params.c (ffffffff81ca90d8)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen.c (ffffffff81d138cc)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff81d20c96)
Location: include/linux/property.h:175
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2bce6)
Location: include/linux/property.h:175
Inline: True
```
```
In drivers/mmc/core/host.c (ffffffff81db66a4)
Location: include/linux/property.h:175
Inline: True
Inline callers:
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
In drivers/gpio/gpiolib.c (ffffffff819454df)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_get_ngpios
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f4e1)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81b199d8)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28333)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/iommu/iommu.c (ffffffff81b762a7)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_init_device
```
```
In drivers/usb/dwc2/params.c (ffffffff81d5dd5c)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen.c (ffffffff81dc94fc)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff81dd69c6)
Location: include/linux/property.h:215
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de1ba6)
Location: include/linux/property.h:215
Inline: True
```
```
In drivers/mmc/core/host.c (ffffffff81e6eb44)
Location: include/linux/property.h:215
Inline: True
Inline callers:
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
In drivers/irqchip/irq-mbigen.c (ffff800010676574)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108917a0)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc1bc)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
```
```
In drivers/usb/dwc2/params.c (ffff800010a3fe70)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffff800010aa3780)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffff800010aa6d98)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffff800010aaf5b4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/power/reset/gpio-poweroff.c (ffff800010ac96e0)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/mmc/core/host.c (ffff800010b30e84)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96fa4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b977fc)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97fdc)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
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
In drivers/usb/dwc2/params.c (c0b129e8)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (c0b83008)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (c0b85888)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c0b910e4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/power/reset/gpio-poweroff.c (c0baa398)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/mmc/core/host.c (c0c0bbd4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/mmc/core/host.c:mmc_of_parse
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2cd20)
Location: include/linux/property.h:136
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
In drivers/usb/dwc2/params.c (c000000000b006a4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (c000000000b843d4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (c000000000b8782c)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c000000000b922fc)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/power/reset/gpio-poweroff.c (c000000000bab4d8)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/mmc/core/host.c (c000000000c2aa1c)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffe00065bc2e)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffe0006b0e84)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffe0006b2de4)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b7ba4)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/power/reset/gpio-poweroff.c (ffffffe0006c77ba)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/mmc/core/host.c (ffffffe000709912)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff817c0421)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/rtc/class.c (ffffffff81817f4a)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/mmc/core/host.c (ffffffff8187a7a5)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817df63a)
Location: include/linux/property.h:136
Inline: True
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
In drivers/usb/dwc2/params.c (ffffffff817fcec1)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81854f9d)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff8185942a)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81860b66)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/mmc/core/host.c (ffffffff818cbc45)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
In drivers/usb/dwc2/params.c (ffffffff81816fd1)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff818700cd)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
```
In drivers/rtc/class.c (ffffffff8187450a)
Location: include/linux/property.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187bd76)
Location: include/linux/property.h:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
```
In drivers/mmc/core/host.c (ffffffff818e8765)
Location: include/linux/property.h:136
Inline: True
Inline callers:
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
