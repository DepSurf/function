# Function: <code>gpiochip_irqchip_irq_valid</code>

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
In drivers/gpio/gpiolib.c (ffffffff8149046b)
Location: drivers/gpio/gpiolib.c:1506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_remove
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
In drivers/gpio/gpiolib.c (ffffffff81499b69)
Location: drivers/gpio/gpiolib.c:1494
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_remove
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
In drivers/gpio/gpiolib.c (ffffffff814d7ca2)
Location: drivers/gpio/gpiolib.c:1525
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815066a0)
Location: drivers/gpio/gpiolib.c:1629
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff815066a0-ffffffff815066e0: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151aca0)
Location: drivers/gpio/gpiolib.c:1629
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff8151aca0-ffffffff8151ace0: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815490a0)
Location: drivers/gpio/gpiolib.c:1648
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff815490a0-ffffffff815490e0: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a120)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff8156a120-ffffffff8156a160: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f02d)
Location: drivers/gpio/gpiolib.c:2000
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff8160fba0-ffffffff8160fbe0: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8163595d)
Location: drivers/gpio/gpiolib.c:947
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff81636280-ffffffff816362c0: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619270)
Location: drivers/gpio/gpiolib.c:936
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff81619270-ffffffff816192b0: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81688540)
Location: drivers/gpio/gpiolib.c:958
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff81688540-ffffffff81688580: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a54b0)
Location: drivers/gpio/gpiolib.c:988
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff817a54b0-ffffffff817a550e: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd170)
Location: drivers/gpio/gpiolib.c:1061
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff818bc640-ffffffff818bc670: gpiochip_irqchip_irq_valid.part.0.isra.0 (STB_LOCAL)
ffffffff818be480-ffffffff818be4de: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8190043e)
Location: drivers/gpio/gpiolib.c:1091
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff818fefb0-ffffffff818fefe0: gpiochip_irqchip_irq_valid.part.0.isra.0 (STB_LOCAL)
ffffffff81901500-ffffffff8190155e: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947cee)
Location: drivers/gpio/gpiolib.c:1257
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff819468b0-ffffffff819468e0: gpiochip_irqchip_irq_valid.part.0.isra.0 (STB_LOCAL)
ffffffff81948e00-ffffffff81948e5e: gpiochip_irqchip_irq_valid (STB_GLOBAL)
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
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bdb10)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffff8000106bdb10-ffff8000106bdb98: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d4b4)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
c085d4b4-c085d538: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000839a40)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
c000000000839a40-c000000000839ab8: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a45ca)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffe0004a45ca-ffffffe0004a463c: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f8e0)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff8155f8e0-ffffffff8155f920: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550730)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff81550730-ffffffff81550770: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e450)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff8155e450-ffffffff8155e490: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool gpiochip_irqchip_irq_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815782e0)
Location: drivers/gpio/gpiolib.c:1671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
**Symbols:**

```
ffffffff815782e0-ffffffff81578320: gpiochip_irqchip_irq_valid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<code>const struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct gpio_chip *gpiochip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
