# Function: <code>i2c_master_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_master_send(const struct i2c_client *client, const char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679da0)
Location: drivers/i2c/i2c-core.c:2284
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_write
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff81679da0-ffffffff81679e0f: i2c_master_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_master_send(const struct i2c_client *client, const char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816db540)
Location: drivers/i2c/i2c-core.c:2489
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff816db540-ffffffff816db5af: i2c_master_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_master_send(const struct i2c_client *client, const char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b880)
Location: drivers/i2c/i2c-core.c:2776
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff8170b880-ffffffff8170b8ef: i2c_master_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_master_send(const struct i2c_client *client, const char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817208f0)
Location: drivers/i2c/i2c-core-base.c:1962
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff817208f0-ffffffff8172095f: i2c_master_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_master_send(const struct i2c_client *client, const char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791c40)
Location: drivers/i2c/i2c-core-base.c:1986
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff81791c40-ffffffff81791caf: i2c_master_send (STB_GLOBAL)
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
In drivers/base/regmap/regmap-i2c.c (ffffffff816a69d5)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff816c0ab6)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816cad8d)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff816cd41b)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff816ce826)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c76c5)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9186)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff816c7515)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff816e1ef6)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ec1bd)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff816ee9de)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff816efe46)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817eed65)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
```
```
In drivers/i2c/i2c-dev.c (ffffffff81800326)
Location: include/linux/i2c.h:108
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff817027b5)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff8171b596)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8172591b)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff81727fe4)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8172957a)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182f995)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
```
```
In drivers/i2c/i2c-dev.c (ffffffff81841685)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81726b05)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff8173f866)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81749bdb)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff8174c293)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174d7ba)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818612c5)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
```
```
In drivers/i2c/i2c-dev.c (ffffffff81873005)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff817e3035)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff817fd306)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81807ba9)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff8180a2d5)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_setup
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180b9ba)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935a5c)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff81947185)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff817f7ca3)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff8180ed26)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81817be9)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff81c149b5)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_setup
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181acfa)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193cb0c)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194cf95)
Location: include/linux/i2c.h:102
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff817dc473)
Location: include/linux/i2c.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff817f3556)
Location: include/linux/i2c.h:105
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fc050)
Location: include/linux/i2c.h:105
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/aat2870-core.c (ffffffff817fe43a)
Location: include/linux/i2c.h:105
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fd3c)
Location: include/linux/i2c.h:105
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff81930b04)
Location: include/linux/i2c.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81867dd3)
Location: include/linux/i2c.h:106
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff8187c476)
Location: include/linux/i2c.h:106
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81885600)
Location: include/linux/i2c.h:106
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/aat2870-core.c (ffffffff81888604)
Location: include/linux/i2c.h:106
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c30de)
Location: include/linux/i2c.h:106
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d3dd1)
Location: include/linux/i2c.h:106
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff819b0603)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff819c4e40)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819ce3b0)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/aat2870-core.c (ffffffff819d171a)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b2356a)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b36601)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81b243d3)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff81b3be55)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b47020)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b4b12a)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5ed7)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccb951)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81b744f3)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff81b8f275)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b9a3f0)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b9e57a)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d567)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d33741)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81bc8343)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff81be3195)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bee3a0)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/aat2870-core.c (ffffffff81bf26da)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd3267)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
```
In drivers/i2c/i2c-dev.c (ffffffff81de9791)
Location: include/linux/i2c.h:107
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffff80001091bc3c)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffff80001093ace4)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffff800010947710)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a300)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffff80001094be58)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab7118)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cd54)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
```
```
In drivers/base/regmap/regmap-i2c.c (c0a01500)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (c0a23668)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (c0a309d8)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (c0a333b8)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (c0a360f8)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (c0b97250)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/char/tpm/tpm_i2c_atmel.c (c000000000965498)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_send
```
```
In drivers/base/regmap/regmap-i2c.c (c0000000009c0340)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (c0000000009e23ec)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f2610)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (c0000000009f5e44)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (c0000000009f7bf0)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (c000000000b9a5c8)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffe00059b73c)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffe0005af64e)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffe0005b989a)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffe0005bc06a)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd44a)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bcd94)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81719fc5)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff81732d26)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173d09b)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff8173f753)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff81740c7a)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855455)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867195)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
In drivers/base/regmap/regmap-i2c.c (ffffffff81735325)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_write
```
```
In drivers/mfd/tps65910.c (ffffffff8174e166)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817584db)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_write
  - drivers/mfd/max8925-i2c.c:max8925_reg_write
```
```
In drivers/mfd/ab3100-core.c (ffffffff8175ab93)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c0ba)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_write
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870585)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_send
```
```
In drivers/i2c/i2c-dev.c (ffffffff81882505)
Location: include/linux/i2c.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_write
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
</ul>
