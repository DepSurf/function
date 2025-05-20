# Function: <code>gpiochip_set_irq_hooks</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b3a0)
Location: drivers/gpio/gpiolib.c:1829
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8151b3a0-ffffffff8151b437: gpiochip_set_irq_hooks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1893
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff815496a0-ffffffff81549720: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff8154ed66-ffffffff8154ed98: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815704a2)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8156bc90-ffffffff8156bd0e: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff815704a2-ffffffff815704c1: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2541
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff8160d310-ffffffff8160d3c7: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff81614281-ffffffff816142a0: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1427
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
**Symbols:**

```
ffffffff816340e0-ffffffff816341a7: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff81bf5aa4-ffffffff81bf5ac3: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161822c)
Location: drivers/gpio/gpiolib.c:1416
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff816874ba)
Location: drivers/gpio/gpiolib.c:1438
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff817a47b5)
Location: drivers/gpio/gpiolib.c:1480
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff818bc3a7)
Location: drivers/gpio/gpiolib.c:1550
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff818ff6d5)
Location: drivers/gpio/gpiolib.c:1581
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
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
In drivers/gpio/gpiolib.c (ffffffff81946b90)
Location: drivers/gpio/gpiolib.c:1762
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bef88)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffff8000106bef88-ffff8000106bf034: gpiochip_set_irq_hooks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085f7a0)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
c085f7a0-c085f864: gpiochip_set_irq_hooks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083ae00)
Location: drivers/gpio/gpiolib.c:2211
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
c00000000083ae00-c00000000083aed0: gpiochip_set_irq_hooks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6652)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffe0004a6652-ffffffe0004a66e2: gpiochip_set_irq_hooks (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81565c62)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81561450-ffffffff815614ce: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff81565c62-ffffffff81565c81: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81556ab2)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff815522a0-ffffffff8155231e: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff81556ab2-ffffffff81556ad1: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815647d2)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8155ffc0-ffffffff8156003e: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff815647d2-ffffffff815647f1: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_irq_hooks(struct gpio_chip *gpiochip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157e6f2)
Location: drivers/gpio/gpiolib.c:2211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81579e30-ffffffff81579eae: gpiochip_set_irq_hooks (STB_LOCAL)
ffffffff8157e6f2-ffffffff8157e711: gpiochip_set_irq_hooks.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *gpiochip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
