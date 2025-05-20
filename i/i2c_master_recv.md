# Function: <code>i2c_master_recv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_master_recv(const struct i2c_client *client, char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679e10)
Location: drivers/i2c/i2c-core.c:2313
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
**Symbols:**

```
ffffffff81679e10-ffffffff81679e82: i2c_master_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_master_recv(const struct i2c_client *client, char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816db5b0)
Location: drivers/i2c/i2c-core.c:2518
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
**Symbols:**

```
ffffffff816db5b0-ffffffff816db622: i2c_master_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_master_recv(const struct i2c_client *client, char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b8f0)
Location: drivers/i2c/i2c-core.c:2805
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
**Symbols:**

```
ffffffff8170b8f0-ffffffff8170b962: i2c_master_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_master_recv(const struct i2c_client *client, char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720960)
Location: drivers/i2c/i2c-core-base.c:1991
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
**Symbols:**

```
ffffffff81720960-ffffffff817209d2: i2c_master_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_master_recv(const struct i2c_client *client, char *buf, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791cb0)
Location: drivers/i2c/i2c-core-base.c:2015
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/aat2870-core.c:__aat2870_read
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
**Symbols:**

```
ffffffff81791cb0-ffffffff81791d22: i2c_master_recv (STB_GLOBAL)
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
In drivers/mfd/ab3100-core.c (ffffffff816cc802)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff816ce9b2)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c91f2)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9244)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff816eddc2)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff816effd2)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817eee55)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
```
```
In drivers/i2c/i2c-dev.c (ffffffff818003e4)
Location: include/linux/i2c.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff81727513)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff817296d2)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182fa45)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
```
```
In drivers/i2c/i2c-dev.c (ffffffff81841b9e)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff8174b7c3)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174d912)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861375)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
```
```
In drivers/i2c/i2c-dev.c (ffffffff8187351e)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff8180984c)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180bb12)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935365)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194721e)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff8181968c)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181ae52)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c3d5)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194d02e)
Location: include/linux/i2c.h:72
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/aat2870-core.c (ffffffff817fe592)
Location: include/linux/i2c.h:75
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f967)
Location: include/linux/i2c.h:75
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff81930b9c)
Location: include/linux/i2c.h:75
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/aat2870-core.c (ffffffff81888772)
Location: include/linux/i2c.h:76
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2717)
Location: include/linux/i2c.h:76
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d3e69)
Location: include/linux/i2c.h:76
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/aat2870-core.c (ffffffff819d18b6)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b22af4)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b36a19)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/aat2870-core.c (ffffffff81b4b306)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb6301)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccbff9)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/aat2870-core.c (ffffffff81b9e756)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d98d)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d33d69)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/aat2870-core.c (ffffffff81bf28b6)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd368d)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/i2c/i2c-dev.c (ffffffff81de9e19)
Location: include/linux/i2c.h:77
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffff8000109499c8)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c030)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab7cf0)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (c0a32858)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (c0a36298)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (c0b97fd8)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/char/tpm/tpm_i2c_atmel.c (c0000000009653e8)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_read_status
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_recv
```
```
In drivers/mfd/ab3100-core.c (c0000000009f4f9c)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (c0000000009f7e40)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (c000000000b9adb8)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffe0005bb642)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd5da)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bcea2)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff8173ec83)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff81740dd2)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855505)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
```
```
In drivers/i2c/i2c-dev.c (ffffffff818676ae)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
In drivers/mfd/ab3100-core.c (ffffffff8175a0c3)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c212)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:__aat2870_read
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870635)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_read
```
```
In drivers/i2c/i2c-dev.c (ffffffff8188295e)
Location: include/linux/i2c.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_read
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
