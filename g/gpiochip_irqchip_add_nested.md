# Function: <code>gpiochip_irqchip_add_nested</code>

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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148b251)
Location: include/linux/gpio/driver.h:328
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81494b7a)
Location: include/linux/gpio/driver.h:308
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0ed1)
Location: include/linux/gpio/driver.h:486
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501e05)
Location: include/linux/gpio/driver.h:505
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815168ee)
Location: include/linux/gpio/driver.h:543
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81544b26)
Location: include/linux/gpio/driver.h:547
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81565a06)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81607b5a)
Location: include/linux/gpio/driver.h:674
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81618aa8)
Location: include/linux/gpio/driver.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069f310)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-stmpe.c (ffff8000106d4f74)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffff8000106d58e4)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (c0841b44)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-stmpe.c (c0870328)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c0870b80)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (c0000000008376a0)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-stmpe.c (c00000000084c2ac)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c00000000084cec4)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2eea)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-stmpe.c (ffffffe0004aff02)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffffffe0004b073a)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559d36)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573bc6)
Location: include/linux/gpio/driver.h:648
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
</details>
</li>
</ul>

## Differences
