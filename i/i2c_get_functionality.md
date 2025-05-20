# Function: <code>i2c_get_functionality</code>

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
In drivers/gpio/gpio-sx150x.c (ffffffff8142b3e0)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff8156a726)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157bb02)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff81587a59)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81593256)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8167a732)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff8167e6ed)
Location: include/linux/i2c.h:607
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/gpio/gpio-sx150x.c (ffffffff81476440)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff815bf56d)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0a24)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff815dcab9)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff815e8096)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff816dc533)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
```
```
In drivers/i2c/i2c-dev.c (ffffffff816df4dc)
Location: include/linux/i2c.h:680
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148b019)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff815ee97d)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd77c)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff81609789)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81614ea6)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700f0c)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8170c873)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-dev.c (ffffffff8170f8bc)
Location: include/linux/i2c.h:718
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81494943)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81602b87)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81611542)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8161d8bd)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81628e9b)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81716761)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f423)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81723706)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81725b05)
Location: include/linux/i2c.h:734
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0bf9)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff8166af47)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679de2)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816860fd)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816917ab)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787960)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790373)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794b26)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff817970e7)
Location: include/linux/i2c.h:736
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501ae3)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff816a692d)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b58ac)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816c20c0)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816cd8cb)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8a01)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d2e92)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d7666)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9d58)
Location: include/linux/i2c.h:825
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815165b3)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff816c746d)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d6b0c)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816e3500)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816eee8b)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f00a1)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817f9fd2)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe7c6)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81800f68)
Location: include/linux/i2c.h:821
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815447d3)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff8170270d)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81712248)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8171d08f)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8172851a)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830500)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183ad0b)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f9c6)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81842275)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815656b3)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81726a5d)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81736548)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8174135f)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8174c76a)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861e30)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186c69b)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81871366)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81873bf5)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81607894)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff817e3200)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f382d)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/twl-core.c (ffffffff817fefed)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8180a7ba)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935660)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81940435)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819454a7)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81947dd5)
Location: include/linux/i2c.h:866
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162c042)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff817f7e60)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:__devm_regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:__regmap_init_i2c
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8180748f)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/twl-core.c (ffffffff8181041d)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8181a0ea)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c6d0)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946523)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194b4e7)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194dbf8)
Location: include/linux/i2c.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160fc61)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff817dc3bd)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec0af)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/twl-core.c (ffffffff817f4a5d)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81c05ea7)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff817fd80a)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191ff67)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81929de9)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192f026)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81931388)
Location: include/linux/i2c.h:883
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167ecf1)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81867e16)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81878c7f)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/twl-core.c (ffffffff8187dabd)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81d0936f)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff818875aa)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2c07)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ccf69)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d2256)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d4664)
Location: include/linux/i2c.h:892
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179a7f1)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff819b0656)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c1188)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/twl-core.c (ffffffff819c5f9b)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81ed179d)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff819d056b)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b2305b)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2efb9)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34a46)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b37345)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b10c1)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81b24436)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/twl-core.c (ffffffff81b3c921)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b44ba2)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b497a2)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb58ed)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2de1)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9b16)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccc775)
Location: include/linux/i2c.h:903
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f4143)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81b74556)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/twl-core.c (ffffffff81b8fd41)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b97ef6)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b9cbed)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cf5b)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a901)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d31840)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d343d3)
Location: include/linux/i2c.h:909
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193b96e)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81bc83a6)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/twl-core.c (ffffffff81be3c61)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81bebec6)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81bf0bdd)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2cad)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de07c1)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de7820)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81dea483)
Location: include/linux/i2c.h:901
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069ef44)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffff80001091bb7c)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092deb8)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (ffff800010930c58)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/twl-core.c (ffff80001093cb7c)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffff80001094ac6c)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/i2c/i2c-core-base.c (ffff800010aaf200)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4f60)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab87d0)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (c0841814)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (c0a01454)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (c0a0f90c)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (c0a11f28)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/twl-core.c (c0a25600)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (c0a338f0)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d230)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_probe
```
```
In drivers/i2c/i2c-core-base.c (c0b90d90)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (c0b96170)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (c0b97d30)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (c0000000008371e0)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/char/tpm/tpm_i2c_atmel.c (c00000000096580c)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_probe
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (c0000000009668fc)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (c000000000967f10)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
```
```
In drivers/base/regmap/regmap-i2c.c (c0000000009c0240)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cd7b4)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (c0000000009d0db4)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/twl-core.c (c0000000009e4808)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (c0000000009f65a4)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/i2c/i2c-core-base.c (c000000000b91e44)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b991ec)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (c000000000b9b7c4)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2c36)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffe00059b6b2)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4ccc)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a717c)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/twl-core.c (ffffffe0005b0e74)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffe0005bc510)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b7886)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bc228)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bd752)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815599e3)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff81719f1d)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729a08)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8173481f)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8173fc2a)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855fc0)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186082b)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff818654f6)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867d85)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573873)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/base/regmap/regmap-i2c.c (ffffffff8173527d)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81744e48)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8174fc5f)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8175b06a)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818710f0)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187ba3b)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff818807a6)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
```
In drivers/i2c/i2c-dev.c (ffffffff81883035)
Location: include/linux/i2c.h:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
</details>
</li>
</ul>

## Differences
