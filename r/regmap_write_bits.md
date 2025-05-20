# Function: <code>regmap_write_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_write_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815667c0)
Location: drivers/base/regmap/regmap.c:2581
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_force_write
```
**Symbols:**

```
ffffffff815667c0-ffffffff81566813: regmap_write_bits (STB_GLOBAL)
```
</details>
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162cb93)
Location: include/linux/regmap.h:1137
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/regmap.h:1137
Inline: True
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81610886)
Location: include/linux/regmap.h:1137
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/regmap.h:1137
Inline: True
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167f967)
Location: include/linux/regmap.h:1177
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/regmap.h:1177
Inline: True
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179b6b6)
Location: include/linux/regmap.h:1202
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/regmap.h:1202
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b1f16)
Location: include/linux/regmap.h:1250
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f4f92)
Location: include/linux/regmap.h:1267
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193c7a2)
Location: include/linux/regmap.h:1267
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple
  - drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set
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
</ul>
