# Function: <code>as3722_gpio_set</code>

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
void as3722_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (ffff800010691e00)
Location: drivers/pinctrl/pinctrl-as3722.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_direction_output
```
**Symbols:**

```
ffff800010691e00-ffff800010691f28: as3722_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void as3722_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (c0833920)
Location: drivers/pinctrl/pinctrl-as3722.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_direction_output
```
**Symbols:**

```
c0833920-c0833a38: as3722_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void as3722_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (c00000000082e1f0)
Location: drivers/pinctrl/pinctrl-as3722.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_direction_output
```
**Symbols:**

```
c00000000082e1f0-c00000000082e34c: as3722_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void as3722_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049d420)
Location: drivers/pinctrl/pinctrl-as3722.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_direction_output
```
**Symbols:**

```
ffffffe00049d420-ffffffe00049d4f4: as3722_gpio_set (STB_LOCAL)
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
