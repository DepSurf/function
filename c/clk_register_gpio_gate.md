# Function: <code>clk_register_gpio_gate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816eb130)
Location: drivers/clk/clk-gpio.c:169
Inline: False
```
**Symbols:**

```
ffffffff816eb130-ffffffff816eb177: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8174fc60)
Location: drivers/clk/clk-gpio.c:182
Inline: False
```
**Symbols:**

```
ffffffff8174fc60-ffffffff8174fcd6: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815384d0)
Location: drivers/clk/clk-gpio.c:182
Inline: False
```
**Symbols:**

```
ffffffff815384d0-ffffffff81538546: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8154b780)
Location: drivers/clk/clk-gpio.c:182
Inline: False
```
**Symbols:**

```
ffffffff8154b780-ffffffff8154b7f2: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815aec10)
Location: drivers/clk/clk-gpio.c:157
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff815aec10-ffffffff815aec7e: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815e6e70)
Location: drivers/clk/clk-gpio.c:157
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff815e6e70-ffffffff815e6edb: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816012a0)
Location: drivers/clk/clk-gpio.c:154
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff816012a0-ffffffff81601305: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81633cd7)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81633c30-ffffffff81633c4c: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81655a07)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81655960-ffffffff8165597c: clk_register_gpio_gate (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffff8000107c796c)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffff8000107c7760-ffff8000107c77c8: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (c08f28f8)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
c08f2780-c08f27b4: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffe000514714)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffe000514554-ffffffe0005145a6: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8161ba67)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff8161b9c0-ffffffff8161b9dc: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8160ff97)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff8160fef0-ffffffff8160ff0c: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81649847)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff816497a0-ffffffff816497bc: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_gate(struct device *dev, const char *name, const char *parent_name, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81663dd7)
Location: drivers/clk/clk-gpio.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81663d30-ffffffff81663d4c: clk_register_gpio_gate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
