# Function: <code>desc_to_gpio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81423f10)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
  - drivers/gpio/gpiolib.c:gpiod_request
  - drivers/gpio/gpiolib.c:gpiod_hog
```
**Symbols:**

```
ffffffff81423f10-ffffffff81423f33: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81472731)
Location: drivers/gpio/gpiolib.c:128
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8146d500-ffffffff8146d523: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81494851)
Location: drivers/gpio/gpiolib.c:131
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8148f3d0-ffffffff8148f3f3: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149e274)
Location: drivers/gpio/gpiolib.c:132
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
```
**Symbols:**

```
ffffffff81498e90-ffffffff81498eb3: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dcdd4)
Location: drivers/gpio/gpiolib.c:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
```
**Symbols:**

```
ffffffff814d7180-ffffffff814d71a3: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150bf4f)
Location: drivers/gpio/gpiolib.c:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff81506340-ffffffff81506363: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81520e7f)
Location: drivers/gpio/gpiolib.c:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff8151a7f0-ffffffff8151a813: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154f2ee)
Location: drivers/gpio/gpiolib.c:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff81548990-ffffffff815489b3: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815707f6)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff81569960-ffffffff81569983: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81614d9f)
Location: drivers/gpio/gpiolib.c:164
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff8160c2f0-ffffffff8160c312: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81bf6631)
Location: drivers/gpio/gpiolib.c:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff816331a0-ffffffff816331c5: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81be851e)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff81616e80-ffffffff81616ea5: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81ce21cb)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff81686100-ffffffff81686125: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81ea8be8)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff817a29e0-ffffffff817a2a0d: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c147d)
Location: drivers/gpio/gpiolib.c:164
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff818b9cb0-ffffffff818b9cdd: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81904426)
Location: drivers/gpio/gpiolib.c:181
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff818fcda0-ffffffff818fcdcd: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194be4f)
Location: drivers/gpio/gpiolib.c:191
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff819443c0-ffffffff819443ea: desc_to_gpio (STB_GLOBAL)
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
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c5434)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffff8000106bd610-ffff8000106bd64c: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0863544)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
c085cca4-c085ccd0: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841fac)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
c000000000838d40-c000000000838d68: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a98c6)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffe0004a3e88-ffffffe0004a3eb8: desc_to_gpio (STB_GLOBAL)
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
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81565fb6)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff8155f120-ffffffff8155f143: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81556e06)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff8154ff70-ffffffff8154ff93: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81564b26)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff8155dc90-ffffffff8155dcb3: desc_to_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int desc_to_gpio(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157ea46)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
**Symbols:**

```
ffffffff81577b20-ffffffff81577b43: desc_to_gpio (STB_GLOBAL)
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
