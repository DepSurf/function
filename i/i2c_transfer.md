# Function: <code>i2c_transfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679cf0)
Location: drivers/i2c/i2c-core.c:2225
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_read
  - drivers/i2c/i2c-core.c:i2c_master_send
  - drivers/i2c/i2c-core.c:i2c_master_recv
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff81679cf0-ffffffff81679d9d: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816db480)
Location: drivers/i2c/i2c-core.c:2430
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_master_recv
  - drivers/i2c/i2c-core.c:i2c_master_send
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
  - drivers/i2c/i2c-core.c:acpi_gsb_i2c_read_bytes
```
**Symbols:**

```
ffffffff816db480-ffffffff816db537: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b7c0)
Location: drivers/i2c/i2c-core.c:2716
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core.c:i2c_master_recv
  - drivers/i2c/i2c-core.c:i2c_master_send
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core.c:acpi_gsb_i2c_read_bytes
```
**Symbols:**

```
ffffffff8170b7c0-ffffffff8170b879: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720820)
Location: drivers/i2c/i2c-core-base.c:1902
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_master_recv
  - drivers/i2c/i2c-core-base.c:i2c_master_send
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81720820-ffffffff817208e1: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791b50)
Location: drivers/i2c/i2c-core-base.c:1926
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_master_recv
  - drivers/i2c/i2c-core-base.c:i2c_master_send
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81791b50-ffffffff81791c32: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d4570)
Location: drivers/i2c/i2c-core-base.c:1909
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d4570-ffffffff817d463f: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fb6f0)
Location: drivers/i2c/i2c-core-base.c:1920
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fb6f0-ffffffff817fb7bf: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183c4b0)
Location: drivers/i2c/i2c-core-base.c:2018
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8183c4b0-ffffffff8183c5b7: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186deb0)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8186deb0-ffffffff8186dfb7: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81941f60)
Location: drivers/i2c/i2c-core-base.c:1953
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff81941f60-ffffffff81942067: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819482b0)
Location: drivers/i2c/i2c-core-base.c:2083
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_get_device_type
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff819482b0-ffffffff819483b7: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192bc10)
Location: drivers/i2c/i2c-core-base.c:2143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff8192bc10-ffffffff8192bd17: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cedd0)
Location: drivers/i2c/i2c-core-base.c:2144
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff819cedd0-ffffffff819ceed4: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b30b50)
Location: drivers/i2c/i2c-core-base.c:2147
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff81b30b50-ffffffff81b30c50: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5480)
Location: drivers/i2c/i2c-core-base.c:2141
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff81cc5480-ffffffff81cc5582: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d110)
Location: drivers/i2c/i2c-core-base.c:2254
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff81d2d110-ffffffff81d2d212: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de2ff0)
Location: drivers/i2c/i2c-core-base.c:2272
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/gpu/drm/drm_edid.c:drm_do_probe_ddc_edid
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes
  - drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffff81de2ff0-ffffffff81de3101: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab17b0)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab17b0-ffff800010ab18d0: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b92824)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_write
  - drivers/rtc/rtc-pcf8523.c:pcf8523_read
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
c0b92824-c0b9296c: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b94680)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
c000000000b94680-c000000000b94814: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9246)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
```
**Symbols:**

```
ffffffe0006b9246-ffffffe0006b931a: i2c_transfer (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81862040)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81862040-ffffffff81862147: i2c_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int i2c_transfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187d2a0)
Location: drivers/i2c/i2c-core-base.c:2023
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write
  - drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8187d2a0-ffffffff8187d3a7: i2c_transfer (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
