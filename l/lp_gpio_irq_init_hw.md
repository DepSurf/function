# Function: <code>lp_gpio_irq_init_hw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a796)
Location: drivers/gpio/gpio-lynxpoint.c:309
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814756e6)
Location: drivers/gpio/gpio-lynxpoint.c:309
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497cb6)
Location: drivers/gpio/gpio-lynxpoint.c:309
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
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
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1974)
Location: drivers/gpio/gpio-lynxpoint.c:309
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
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
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e034a)
Location: drivers/gpio/gpio-lynxpoint.c:309
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
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
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f6d3)
Location: drivers/gpio/gpio-lynxpoint.c:309
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
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
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524d83)
Location: drivers/gpio/gpio-lynxpoint.c:297
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
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
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155343f)
Location: drivers/gpio/gpio-lynxpoint.c:297
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lp_gpio_irq_init_hw(struct gpio_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81574310)
Location: drivers/gpio/gpio-lynxpoint.c:303
Inline: False
```
**Symbols:**

```
ffffffff81574310-ffffffff81574395: lp_gpio_irq_init_hw (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lp_gpio_irq_init_hw(struct gpio_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155a920)
Location: drivers/gpio/gpio-lynxpoint.c:303
Inline: False
```
**Symbols:**

```
ffffffff8155a920-ffffffff8155a9a5: lp_gpio_irq_init_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lp_gpio_irq_init_hw(struct gpio_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568640)
Location: drivers/gpio/gpio-lynxpoint.c:303
Inline: False
```
**Symbols:**

```
ffffffff81568640-ffffffff815686c5: lp_gpio_irq_init_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lp_gpio_irq_init_hw(struct gpio_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582560)
Location: drivers/gpio/gpio-lynxpoint.c:303
Inline: False
```
**Symbols:**

```
ffffffff81582560-ffffffff815825e5: lp_gpio_irq_init_hw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
