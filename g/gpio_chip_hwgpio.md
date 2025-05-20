# Function: <code>gpio_chip_hwgpio</code>

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
In drivers/gpio/gpiolib.c (ffffffff814240ab)
Location: drivers/gpio/gpiolib.h:114
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
  - drivers/gpio/gpiolib.c:gpiod_hog
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8142778a)
Location: drivers/gpio/gpiolib.h:114
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff814726d2)
Location: drivers/gpio/gpiolib.h:180
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81472a7a)
Location: drivers/gpio/gpiolib.h:180
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff814947f2)
Location: drivers/gpio/gpiolib.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81494c9a)
Location: drivers/gpio/gpiolib.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8149e219)
Location: drivers/gpio/gpiolib.h:222
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_request
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149e69a)
Location: drivers/gpio/gpiolib.h:222
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff814dcd79)
Location: drivers/gpio/gpiolib.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd1da)
Location: drivers/gpio/gpiolib.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8150b16a)
Location: drivers/gpio/gpiolib.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150ce7c)
Location: drivers/gpio/gpiolib.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8151fbd3)
Location: drivers/gpio/gpiolib.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815223ac)
Location: drivers/gpio/gpiolib.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8154dd0d)
Location: drivers/gpio/gpiolib.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815508c3)
Location: drivers/gpio/gpiolib.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8156ef0d)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81571d73)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff816133cd)
Location: drivers/gpio/gpiolib.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816163fe)
Location: drivers/gpio/gpiolib.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff81638296)
Location: drivers/gpio/gpiolib.h:147
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81639b13)
Location: drivers/gpio/gpiolib.h:147
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163cd8e)
Location: drivers/gpio/gpiolib.h:147
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8161bdd6)
Location: drivers/gpio/gpiolib.h:147
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161d763)
Location: drivers/gpio/gpiolib.h:147
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816208be)
Location: drivers/gpio/gpiolib.h:147
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8168b301)
Location: drivers/gpio/gpiolib.h:159
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168cdd3)
Location: drivers/gpio/gpiolib.h:159
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168fe8e)
Location: drivers/gpio/gpiolib.h:159
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff817a4cf1)
Location: drivers/gpio/gpiolib.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aaae1)
Location: drivers/gpio/gpiolib.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817aef23)
Location: drivers/gpio/gpiolib.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff818c1075)
Location: drivers/gpio/gpiolib.h:214
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c36f1)
Location: drivers/gpio/gpiolib.h:214
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:linereq_show_fdinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c84f6)
Location: drivers/gpio/gpiolib.h:214
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff81904057)
Location: drivers/gpio/gpiolib.h:224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819067c1)
Location: drivers/gpio/gpiolib.h:224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:linereq_show_fdinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b4ac)
Location: drivers/gpio/gpiolib.h:224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8194ba97)
Location: drivers/gpio/gpiolib.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950b61)
Location: drivers/gpio/gpiolib.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:linereq_show_fdinfo
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff819531ca)
Location: drivers/gpio/gpiolib.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffff8000106c4e3c)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c98f4)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (c08630e0)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (c0866c58)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (c00000000084199c)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (c0000000008475f0)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffe0004a94a8)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004acbb4)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff815646cd)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81567533)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155551d)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81558383)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8156323d)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815660a3)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
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
In drivers/gpio/gpiolib.c (ffffffff8157d15d)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_to_irq
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157ffc3)
Location: drivers/gpio/gpiolib.h:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
</details>
</li>
</ul>

## Differences
