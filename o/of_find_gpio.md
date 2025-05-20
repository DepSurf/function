# Function: <code>of_find_gpio</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-of.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-of.h:20
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-of.h:20
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-of.h:28
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-of.h:26
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-of.h:26
Inline: True
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
struct gpio_desc *of_find_gpio(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c82e0)
Location: drivers/gpio/gpiolib-of.c:477
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-of.c:of_find_gpio
```
**Symbols:**

```
ffff8000106c82e0-ffff8000106c862c: of_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *of_find_gpio(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c08658c4)
Location: drivers/gpio/gpiolib-of.c:477
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-of.c:of_find_gpio
```
**Symbols:**

```
c08658c4-c0865c54: of_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *of_find_gpio(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0000000008458b0)
Location: drivers/gpio/gpiolib-of.c:477
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-of.c:of_find_gpio
```
**Symbols:**

```
c0000000008458b0-c000000000845e5c: of_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *of_find_gpio(struct device *dev, const char *con_id, unsigned int idx, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004abac6)
Location: drivers/gpio/gpiolib-of.c:477
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-of.c:of_find_gpio
```
**Symbols:**

```
ffffffe0004abac6-ffffffe0004abe54: of_find_gpio (STB_GLOBAL)
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
