# Function: <code>tc3589x_gpio_set</code>

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
void tc3589x_gpio_set(struct gpio_chip *chip, unsigned int offset, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tc3589x.c (ffff8000106d55a8)
Location: drivers/gpio/gpio-tc3589x.c:52
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
ffff8000106d55a8-ffff8000106d5644: tc3589x_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tc3589x_gpio_set(struct gpio_chip *chip, unsigned int offset, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tc3589x.c (c0870874)
Location: drivers/gpio/gpio-tc3589x.c:52
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
c0870874-c0870910: tc3589x_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tc3589x_gpio_set(struct gpio_chip *chip, unsigned int offset, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tc3589x.c (c00000000084cad0)
Location: drivers/gpio/gpio-tc3589x.c:52
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
c00000000084cad0-c00000000084cb8c: tc3589x_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tc3589x_gpio_set(struct gpio_chip *chip, unsigned int offset, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tc3589x.c (ffffffe0004b0456)
Location: drivers/gpio/gpio-tc3589x.c:52
Inline: False
Direct callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output
```
**Symbols:**

```
ffffffe0004b0456-ffffffe0004b04ca: tc3589x_gpio_set (STB_LOCAL)
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
