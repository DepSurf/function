# Function: <code>gpiod_get_value_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425be0)
Location: drivers/gpio/gpiolib.c:1679
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81425be0-ffffffff81425c12: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146f500)
Location: drivers/gpio/gpiolib.c:2689
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8146f500-ffffffff8146f59c: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491860)
Location: drivers/gpio/gpiolib.c:2898
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81491860-ffffffff814918fc: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149b480)
Location: drivers/gpio/gpiolib.c:2905
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8149b480-ffffffff8149b52e: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814da320)
Location: drivers/gpio/gpiolib.c:3176
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff814da320-ffffffff814da3ce: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509090)
Location: drivers/gpio/gpiolib.c:3367
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81509090-ffffffff815090cd: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d730)
Location: drivers/gpio/gpiolib.c:3609
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8151d730-ffffffff8151d76d: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b790)
Location: drivers/gpio/gpiolib.c:3698
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8154b790-ffffffff8154b7cd: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156ca20)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8156ca20-ffffffff8156ca5d: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160ff78)
Location: drivers/gpio/gpiolib.c:4465
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81614947-ffffffff816149a4: gpiod_get_value_cansleep.cold (STB_LOCAL)
ffffffff816108c0-ffffffff8161091f: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636ce9)
Location: drivers/gpio/gpiolib.c:3289
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81bf61b0-ffffffff81bf620d: gpiod_get_value_cansleep.cold (STB_LOCAL)
ffffffff81636cb0-ffffffff81636d0f: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161a609)
Location: drivers/gpio/gpiolib.c:3266
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81be8056-ffffffff81be80b3: gpiod_get_value_cansleep.cold (STB_LOCAL)
ffffffff8161a5d0-ffffffff8161a62f: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81689a09)
Location: drivers/gpio/gpiolib.c:3325
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81ce1bfb-ffffffff81ce1c58: gpiod_get_value_cansleep.cold (STB_LOCAL)
ffffffff816899d0-ffffffff81689a2f: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a696d)
Location: drivers/gpio/gpiolib.c:3446
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81ea8468-ffffffff81ea84c5: gpiod_get_value_cansleep.cold (STB_LOCAL)
ffffffff817a6930-ffffffff817a699a: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818befe0)
Location: drivers/gpio/gpiolib.c:3516
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff818befe0-ffffffff818bf097: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81902120)
Location: drivers/gpio/gpiolib.c:3557
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl_unlocked
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81902120-ffffffff819021cf: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949c60)
Location: drivers/gpio/gpiolib.c:3750
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81949c60-ffffffff81949d07: gpiod_get_value_cansleep (STB_GLOBAL)
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
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfdb8)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffff8000106bfdb8-ffff8000106bfe18: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08605ec)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
  - sound/soc/soc-jack.c:gpio_work
```
**Symbols:**

```
c08605ec-c086063c: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083dee0)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
c00000000083dee0-c00000000083df50: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a72ce)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffe0004a72ce-ffffffe0004a731e: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815621e0)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff815621e0-ffffffff8156221d: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81553030)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
**Symbols:**

```
ffffffff81553030-ffffffff8155306d: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560d50)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81560d50-ffffffff81560d8d: gpiod_get_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157ac10)
Location: drivers/gpio/gpiolib.c:4052
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib-sysfs.c:value_show
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8157ac10-ffffffff8157ac4d: gpiod_get_value_cansleep (STB_GLOBAL)
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
