# Function: <code>of_get_named_gpiod_flags</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.h:107
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.h:110
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.h:110
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.h:114
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.h:111
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.h:112
Inline: True
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct gpio_desc *of_get_named_gpiod_flags(struct device_node *np, const char *propname, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c7948)
Location: drivers/gpio/gpiolib-of.c:249
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
```
**Symbols:**

```
ffff8000106c7948-ffff8000106c7d4c: of_get_named_gpiod_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *of_get_named_gpiod_flags(struct device_node *np, const char *propname, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0865124)
Location: drivers/gpio/gpiolib-of.c:249
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
```
**Symbols:**

```
c0865124-c0865548: of_get_named_gpiod_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *of_get_named_gpiod_flags(struct device_node *np, const char *propname, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c000000000844580)
Location: drivers/gpio/gpiolib-of.c:249
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
```
**Symbols:**

```
c000000000844580-c000000000845068: of_get_named_gpiod_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *of_get_named_gpiod_flags(struct device_node *np, const char *propname, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab276)
Location: drivers/gpio/gpiolib-of.c:249
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:of_find_gpio
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-of.c:of_get_named_gpio_flags
```
**Symbols:**

```
ffffffe0004ab276-ffffffe0004ab626: of_get_named_gpiod_flags (STB_LOCAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
