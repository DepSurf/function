# Function: <code>gpiochip_hierarchy_add_domain</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156fa96)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (ffffffff8160de65)
Location: drivers/gpio/gpiolib.c:2268
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816346cc)
Location: drivers/gpio/gpiolib.c:1154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1143
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff81617f30-ffffffff81618113: gpiochip_hierarchy_add_domain.constprop.0 (STB_LOCAL)
ffffffff81be79a6-ffffffff81be7a31: gpiochip_hierarchy_add_domain.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1165
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff816871b0-ffffffff81687393: gpiochip_hierarchy_add_domain.constprop.0 (STB_LOCAL)
ffffffff81ce1472-ffffffff81ce14fd: gpiochip_hierarchy_add_domain.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1195
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff817a4450-ffffffff817a4682: gpiochip_hierarchy_add_domain.constprop.0 (STB_LOCAL)
ffffffff81ea7cf3-ffffffff81ea7d83: gpiochip_hierarchy_add_domain.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bbfb0)
Location: drivers/gpio/gpiolib.c:1271
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff818bbfb0-ffffffff818bc25b: gpiochip_hierarchy_add_domain.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ff2e0)
Location: drivers/gpio/gpiolib.c:1295
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff818ff2e0-ffffffff818ff58b: gpiochip_hierarchy_add_domain.constprop.0 (STB_LOCAL)
```
</details>
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
In drivers/gpio/gpiolib.c (ffff8000106c5c04)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (c0863cbc)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2023
Inline: True
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
In drivers/gpio/gpiolib.c (ffffffe0004a9f2e)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (ffffffff81565256)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (ffffffff815560a6)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (ffffffff81563dc6)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
In drivers/gpio/gpiolib.c (ffffffff8157dce6)
Location: drivers/gpio/gpiolib.c:1959
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
</ul>

## Differences
