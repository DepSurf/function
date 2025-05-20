# Function: <code>i2c_smbus_xfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167a3b0)
Location: drivers/i2c/i2c-core.c:3022
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-core.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff8167a3b0-ffffffff8167a6ea: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dbb20)
Location: drivers/i2c/i2c-core.c:3227
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-core.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff816dbb20-ffffffff816dbe56: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170be60)
Location: drivers/i2c/i2c-core.c:3515
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-core.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_default_probe
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff8170be60-ffffffff8170c196: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81722e70)
Location: drivers/i2c/i2c-core-smbus.c:482
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81722e70-ffffffff8172318e: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794270)
Location: drivers/i2c/i2c-core-smbus.c:484
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81794270-ffffffff817945ae: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6dd0)
Location: drivers/i2c/i2c-core-smbus.c:527
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff817d6dd0-ffffffff817d7103: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe1e0)
Location: drivers/i2c/i2c-core-smbus.c:527
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff817fe1e0-ffffffff817fe263: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f3b0)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff8183f3b0-ffffffff8183f49d: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870d50)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81870d50-ffffffff81870e3d: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944d90)
Location: drivers/i2c/i2c-core-smbus.c:532
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81944d90-ffffffff81944e7d: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194add0)
Location: drivers/i2c/i2c-core-smbus.c:532
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff8194add0-ffffffff8194aebd: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e910)
Location: drivers/i2c/i2c-core-smbus.c:526
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff8192e910-ffffffff8192e9fd: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1b40)
Location: drivers/i2c/i2c-core-smbus.c:534
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff819d1b40-ffffffff819d1c2d: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34110)
Location: drivers/i2c/i2c-core-smbus.c:535
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81b34110-ffffffff81b3420d: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9100)
Location: drivers/i2c/i2c-core-smbus.c:535
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81cc9100-ffffffff81cc9202: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30e20)
Location: drivers/i2c/i2c-core-smbus.c:535
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81d30e20-ffffffff81d30f22: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6df0)
Location: drivers/i2c/i2c-core-smbus.c:535
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81de6df0-ffffffff81de6f0b: i2c_smbus_xfer (STB_GLOBAL)
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
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4930)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffff800010ab4930-ffff800010ab4a48: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95b54)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
c0b95b54-c0b95c74: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98af0)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
c000000000b98af0-c000000000b98c78: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbe2c)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffe0006bbe2c-ffffffe0006bbeec: i2c_smbus_xfer (STB_GLOBAL)
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
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864ee0)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81864ee0-ffffffff81864fcd: i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880190)
Location: drivers/i2c/i2c-core-smbus.c:525
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_default_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_device_id
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
```
**Symbols:**

```
ffffffff81880190-ffffffff8188027d: i2c_smbus_xfer (STB_GLOBAL)
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
