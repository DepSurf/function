# Function: <code>gpiochip_set_cascaded_irqchip</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490fcc)
Location: drivers/gpio/gpiolib.c:1525
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_chained_irqchip
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_chained_irqchip
```
**Symbols:**

```
ffffffff81490f50-ffffffff81490fb5: gpiochip_set_cascaded_irqchip.isra.43.part.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149aa8c)
Location: drivers/gpio/gpiolib.c:1513
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_chained_irqchip
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_chained_irqchip
```
**Symbols:**

```
ffffffff8149aa20-ffffffff8149aa75: gpiochip_set_cascaded_irqchip.isra.45.part.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9366)
Location: drivers/gpio/gpiolib.c:1544
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
**Symbols:**

```
ffffffff814d8ea0-ffffffff814d8efb: gpiochip_set_cascaded_irqchip.isra.44.part.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508010)
Location: drivers/gpio/gpiolib.c:1651
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
**Symbols:**

```
ffffffff81508010-ffffffff815080f0: gpiochip_set_cascaded_irqchip.isra.31 (STB_LOCAL)
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
In drivers/gpio/gpiolib.c (ffffffff8151d075)
Location: drivers/gpio/gpiolib.c:1650
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff8154b185)
Location: drivers/gpio/gpiolib.c:1669
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff8156c365)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160dca5)
Location: drivers/gpio/gpiolib.c:2021
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf6a0)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
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
In drivers/gpio/gpiolib.c (c085fd78)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d300)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6b96)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561b25)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552975)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560695)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff8157a505)
Location: drivers/gpio/gpiolib.c:1692
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_set_nested_irqchip
```
</details>
</li>
</ul>

## Differences
