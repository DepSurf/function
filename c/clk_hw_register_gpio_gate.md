# Function: <code>clk_hw_register_gpio_gate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8174fc69)
Location: drivers/clk/clk-gpio.c:171
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff8174fb90-ffffffff8174fbd7: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815384d9)
Location: drivers/clk/clk-gpio.c:171
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff81538400-ffffffff81538447: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8154b789)
Location: drivers/clk/clk-gpio.c:171
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff8154b6c0-ffffffff8154b701: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815aec19)
Location: drivers/clk/clk-gpio.c:146
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff815aebd0-ffffffff815aec0e: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815e6e9e)
Location: drivers/clk/clk-gpio.c:146
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff815e6e30-ffffffff815e6e6b: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816012bc)
Location: drivers/clk/clk-gpio.c:143
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff81601260-ffffffff81601295: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81633bb0)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81633bb0-ffffffff81633c23: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816558e0)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff816558e0-ffffffff81655953: clk_hw_register_gpio_gate (STB_GLOBAL)
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
In drivers/clk/clk-gpio.c (ffffffff817059c9)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff81722cb9)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff81703f59)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff8177ed59)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff818b5c58)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff81a02d18)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff81a4bb68)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
In drivers/clk/clk-gpio.c (ffffffff81a977b8)
Location: drivers/clk/clk-gpio.c:173
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
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
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffff8000107c76e0)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffff8000107c76e0-ffff8000107c7760: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (c08f2704)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
c08f2704-c08f2780: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffe0005144dc)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffe0005144dc-ffffffe000514554: clk_hw_register_gpio_gate (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8161b940)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff8161b940-ffffffff8161b9b3: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8160fe70)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff8160fe70-ffffffff8160fee3: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81649720)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81649720-ffffffff81649793: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81663cb0)
Location: drivers/clk/clk-gpio.c:172
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81663cb0-ffffffff81663d23: clk_hw_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_desc *gpiod</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int gpio</code>
</li>
<li>
<b>Param removed. </b>
<code>bool active_low</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, name, parent_name, gpio, active_low, flags</code> ➡️ <code>dev, name, parent_name, gpiod, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
