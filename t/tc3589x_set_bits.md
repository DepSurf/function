# Function: <code>tc3589x_set_bits</code>

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
int tc3589x_set_bits(struct tc3589x *tc3589x, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (ffff800010930a08)
Location: drivers/mfd/tc3589x.c:123
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
ffff800010930a08-ffff800010930a88: tc3589x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc3589x_set_bits(struct tc3589x *tc3589x, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (c0a11d48)
Location: drivers/mfd/tc3589x.c:123
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
c0a11d48-c0a11db0: tc3589x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc3589x_set_bits(struct tc3589x *tc3589x, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (c0000000009d0a80)
Location: drivers/mfd/tc3589x.c:123
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
c0000000009d0a80-c0000000009d0b30: tc3589x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc3589x_set_bits(struct tc3589x *tc3589x, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/tc3589x.c (ffffffe0005a6f2c)
Location: drivers/mfd/tc3589x.c:123
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
ffffffe0005a6f2c-ffffffe0005a6fa6: tc3589x_set_bits (STB_GLOBAL)
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
