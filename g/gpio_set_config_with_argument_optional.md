# Function: <code>gpio_set_config_with_argument_optional</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int gpio_set_config_with_argument_optional(struct gpio_desc *desc, enum pin_config_param mode, u32 argument);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816370f5)
Location: drivers/gpio/gpiolib.c:2137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff81635150-ffffffff816351df: gpio_set_config_with_argument_optional (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int gpio_set_config_with_argument_optional(struct gpio_desc *desc, enum pin_config_param mode, u32 argument);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161aa15)
Location: drivers/gpio/gpiolib.c:2114
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff816197f0-ffffffff8161987f: gpio_set_config_with_argument_optional (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int gpio_set_config_with_argument_optional(struct gpio_desc *desc, enum pin_config_param mode, u32 argument);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81689e55)
Location: drivers/gpio/gpiolib.c:2133
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
**Symbols:**

```
ffffffff81688c10-ffffffff81688c9c: gpio_set_config_with_argument_optional (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a541e)
Location: drivers/gpio/gpiolib.c:2194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd68e)
Location: drivers/gpio/gpiolib.c:2264
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819007be)
Location: drivers/gpio/gpiolib.c:2305
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194a02e)
Location: drivers/gpio/gpiolib.c:2499
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
  - drivers/gpio/gpiolib.c:gpio_set_bias
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
