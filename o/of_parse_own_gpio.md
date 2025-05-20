# Function: <code>of_parse_own_gpio</code>

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
struct gpio_desc *of_parse_own_gpio(struct device_node *np, struct gpio_chip *chip, unsigned int idx, const char **name, long unsigned int *lflags, enum gpiod_flags *dflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c7eb0)
Location: drivers/gpio/gpiolib-of.c:558
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffff8000106c7eb0-ffff8000106c80d4: of_parse_own_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0865f28)
Location: drivers/gpio/gpiolib-of.c:558
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *of_parse_own_gpio(struct device_node *np, struct gpio_chip *chip, unsigned int idx, const char **name, long unsigned int *lflags, enum gpiod_flags *dflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c000000000845230)
Location: drivers/gpio/gpiolib-of.c:558
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c000000000845230-c00000000084553c: of_parse_own_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *of_parse_own_gpio(struct device_node *np, struct gpio_chip *chip, unsigned int idx, const char **name, long unsigned int *lflags, enum gpiod_flags *dflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab74e)
Location: drivers/gpio/gpiolib-of.c:558
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffffffe0004ab74e-ffffffe0004ab90c: of_parse_own_gpio (STB_LOCAL)
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
