# Function: <code>gpiod_direction_input</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425cc0)
Location: drivers/gpio/gpiolib.c:1100
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81425cc0-ffffffff81425dfa: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146fe90)
Location: drivers/gpio/gpiolib.c:2055
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8146fe90-ffffffff81470027: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81492200)
Location: drivers/gpio/gpiolib.c:2242
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81492200-ffffffff81492397: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149bca0)
Location: drivers/gpio/gpiolib.c:2243
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8149bca0-ffffffff8149be19: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8ac0)
Location: drivers/gpio/gpiolib.c:2385
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff814d8ac0-ffffffff814d8c3f: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2499
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8150bdb7-ffffffff8150bded: gpiod_direction_input.cold.46 (STB_LOCAL)
ffffffff815078e0-ffffffff815079bb: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2537
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81520c37-ffffffff81520cc3: gpiod_direction_input.cold.44 (STB_LOCAL)
ffffffff8151c800-ffffffff8151c914: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2626
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff8154eea4-ffffffff8154ef2f: gpiod_direction_input.cold (STB_LOCAL)
ffffffff8154aa90-ffffffff8154abfb: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81570417-ffffffff815704a2: gpiod_direction_input.cold (STB_LOCAL)
ffffffff8156b980-ffffffff8156baeb: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3366
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81614460-ffffffff816144eb: gpiod_direction_input.cold (STB_LOCAL)
ffffffff8160ee30-ffffffff8160efa1: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2209
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81bf5cd4-ffffffff81bf5d6e: gpiod_direction_input.cold (STB_LOCAL)
ffffffff816356b0-ffffffff81635825: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81be7bd6-ffffffff81be7c70: gpiod_direction_input.cold (STB_LOCAL)
ffffffff81619880-ffffffff816199e5: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2215
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81ce1760-ffffffff81ce17fa: gpiod_direction_input.cold (STB_LOCAL)
ffffffff81688ca0-ffffffff81688e02: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2276
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81ea7fe4-ffffffff81ea8077: gpiod_direction_input.cold (STB_LOCAL)
ffffffff817a5ac0-ffffffff817a5bf0: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd7d0)
Location: drivers/gpio/gpiolib.c:2346
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff818bd7d0-ffffffff818bd993: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900900)
Location: drivers/gpio/gpiolib.c:2387
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81900900-ffffffff81900ac3: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81948160)
Location: drivers/gpio/gpiolib.c:2581
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81948160-ffffffff819482fb: gpiod_direction_input (STB_GLOBAL)
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
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c0d08)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffff8000106c0d08-ffff8000106c0f6c: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085f580)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
c085f580-c085f7a0: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083c880)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
c00000000083c880-c00000000083cb5c: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a63b8)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffe0004a63b8-ffffffe0004a657e: gpiod_direction_input (STB_GLOBAL)
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
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81565bd7-ffffffff81565c62: gpiod_direction_input.cold (STB_LOCAL)
ffffffff81561140-ffffffff815612ab: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81556a27-ffffffff81556ab2: gpiod_direction_input.cold (STB_LOCAL)
ffffffff81551f90-ffffffff815520fb: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff81564747-ffffffff815647d2: gpiod_direction_input.cold (STB_LOCAL)
ffffffff8155fcb0-ffffffff8155fe1b: gpiod_direction_input (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiod_direction_input(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:direction_store
```
**Symbols:**

```
ffffffff8157e667-ffffffff8157e6f2: gpiod_direction_input.cold (STB_LOCAL)
ffffffff81579b10-ffffffff81579c8b: gpiod_direction_input (STB_GLOBAL)
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
