# Function: <code>validate_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2306
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff81506bb0-ffffffff81506c07: validate_desc (STB_LOCAL)
ffffffff8150bd78-ffffffff8150bda1: validate_desc.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2334
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff8151b0f0-ffffffff8151b147: validate_desc (STB_LOCAL)
ffffffff81520bf8-ffffffff81520c21: validate_desc.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2398
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff81549160-ffffffff815491a4: validate_desc (STB_LOCAL)
ffffffff8154ecea-ffffffff8154ed2d: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8156a550-ffffffff8156a594: validate_desc (STB_LOCAL)
ffffffff815701df-ffffffff81570222: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81610755)
Location: drivers/gpio/gpiolib.c:3097
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8160cd70-ffffffff8160cdb7: validate_desc (STB_LOCAL)
ffffffff816141f2-ffffffff81614235: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636aa5)
Location: drivers/gpio/gpiolib.c:1901
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff81633aa0-ffffffff81633ae7: validate_desc (STB_LOCAL)
ffffffff81bf5a15-ffffffff81bf5a58: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161a415)
Location: drivers/gpio/gpiolib.c:1878
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff81617650-ffffffff81617697: validate_desc (STB_LOCAL)
ffffffff81be7919-ffffffff81be795c: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816897b5)
Location: drivers/gpio/gpiolib.c:1900
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff816868d0-ffffffff81686917: validate_desc (STB_LOCAL)
ffffffff81ce13e5-ffffffff81ce1428: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a6725)
Location: drivers/gpio/gpiolib.c:1961
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff817a3640-ffffffff817a3692: validate_desc (STB_LOCAL)
ffffffff81ea7bb3-ffffffff81ea7bf6: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be6b5)
Location: drivers/gpio/gpiolib.c:2031
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff818bab80-ffffffff818bac05: validate_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901795)
Location: drivers/gpio/gpiolib.c:2070
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff818fdc80-ffffffff818fdd05: validate_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949317)
Location: drivers/gpio/gpiolib.c:2253
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_config
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff819451e0-ffffffff81945265: validate_desc (STB_LOCAL)
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
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bdc10)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffff8000106bdc10-ffff8000106bdcb4: validate_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d928)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
c085d928-c085d9b8: validate_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a1a0)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
c00000000083a1a0-c00000000083a290: validate_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4ada)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffe0004a4ada-ffffffe0004a4b6a: validate_desc (STB_LOCAL)
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
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8155fd10-ffffffff8155fd54: validate_desc (STB_LOCAL)
ffffffff8156599f-ffffffff815659e2: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff81550b60-ffffffff81550ba4: validate_desc (STB_LOCAL)
ffffffff815567ef-ffffffff81556832: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff8155e880-ffffffff8155e8c4: validate_desc (STB_LOCAL)
ffffffff8156450f-ffffffff81564552: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int validate_desc(const struct gpio_desc *desc, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2730
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_get_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_toggle_active_low
  - drivers/gpio/gpiolib.c:gpiod_is_active_low
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_request
```
**Symbols:**

```
ffffffff81578710-ffffffff81578754: validate_desc (STB_LOCAL)
ffffffff8157e42f-ffffffff8157e472: validate_desc.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
