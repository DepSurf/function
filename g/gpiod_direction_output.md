# Function: <code>gpiod_direction_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426040)
Location: drivers/gpio/gpiolib.c:1198
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
**Symbols:**

```
ffffffff81426040-ffffffff81426087: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81470360)
Location: drivers/gpio/gpiolib.c:2169
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81470360-ffffffff814703fb: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814926d0)
Location: drivers/gpio/gpiolib.c:2357
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff814926d0-ffffffff81492775: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149c120)
Location: drivers/gpio/gpiolib.c:2359
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8149c120-ffffffff8149c1d7: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9900)
Location: drivers/gpio/gpiolib.c:2469
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff814d9900-ffffffff814d9a8a: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8150beaf-ffffffff8150bee4: gpiod_direction_output.cold.50 (STB_LOCAL)
ffffffff81508e00-ffffffff81508ee6: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2662
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff81520dce-ffffffff81520e14: gpiod_direction_output.cold.48 (STB_LOCAL)
ffffffff8151db40-ffffffff8151dc2f: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2750
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8154f11e-ffffffff8154f166: gpiod_direction_output.cold (STB_LOCAL)
ffffffff8154bc50-ffffffff8154bd40: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8157067a-ffffffff815706c2: gpiod_direction_output.cold (STB_LOCAL)
ffffffff8156ce30-ffffffff8156cf2b: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3485
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_set_config
```
**Symbols:**

```
ffffffff81614c06-ffffffff81614c4e: gpiod_direction_output.cold (STB_LOCAL)
ffffffff816111b0-ffffffff8161132b: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2328
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
```
**Symbols:**

```
ffffffff81bf5ee1-ffffffff81bf5f2f: gpiod_direction_output.cold (STB_LOCAL)
ffffffff816368d0-ffffffff81636a44: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2305
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81be7d87-ffffffff81be7dd5: gpiod_direction_output.cold (STB_LOCAL)
ffffffff8161a200-ffffffff8161a36c: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2334
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81ce1911-ffffffff81ce195f: gpiod_direction_output.cold (STB_LOCAL)
ffffffff816895f0-ffffffff8168975c: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2395
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81ea8186-ffffffff81ea81d2: gpiod_direction_output.cold (STB_LOCAL)
ffffffff817a6290-ffffffff817a63a2: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be2e0)
Location: drivers/gpio/gpiolib.c:2465
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff818be2e0-ffffffff818be469: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901390)
Location: drivers/gpio/gpiolib.c:2506
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81901390-ffffffff819014ee: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948c90)
Location: drivers/gpio/gpiolib.c:2700
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81948c90-ffffffff81948de2: gpiod_direction_output (STB_GLOBAL)
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
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c24b8)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
```
**Symbols:**

```
ffff8000106c24b8-ffff8000106c2620: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860b1c)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
```
**Symbols:**

```
c0860b1c-c0860c84: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083e5c0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
```
**Symbols:**

```
c00000000083e5c0-c00000000083e7dc: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7698)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
```
**Symbols:**

```
ffffffe0004a7698-ffffffe0004a779c: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff81565e3a-ffffffff81565e82: gpiod_direction_output.cold (STB_LOCAL)
ffffffff815625f0-ffffffff815626eb: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff81556c8a-ffffffff81556cd2: gpiod_direction_output.cold (STB_LOCAL)
ffffffff81553440-ffffffff8155353b: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff815649aa-ffffffff815649f2: gpiod_direction_output.cold (STB_LOCAL)
ffffffff81561160-ffffffff8156125b: gpiod_direction_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_output(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8157e8ca-ffffffff8157e912: gpiod_direction_output.cold (STB_LOCAL)
ffffffff8157b050-ffffffff8157b14b: gpiod_direction_output (STB_GLOBAL)
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
