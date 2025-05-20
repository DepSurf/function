# Function: <code>clk_hw_register_gpio_mux</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8174fbe0)
Location: drivers/clk/clk-gpio.c:206
Inline: False
```
**Symbols:**

```
ffffffff8174fbe0-ffffffff8174fc28: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81538450)
Location: drivers/clk/clk-gpio.c:206
Inline: False
```
**Symbols:**

```
ffffffff81538450-ffffffff81538498: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8154b710)
Location: drivers/clk/clk-gpio.c:206
Inline: False
```
**Symbols:**

```
ffffffff8154b710-ffffffff8154b74d: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815aed30)
Location: drivers/clk/clk-gpio.c:179
Inline: False
```
**Symbols:**

```
ffffffff815aed30-ffffffff815aed65: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:179
Inline: False
```
**Symbols:**

```
ffffffff815e6ff2-ffffffff815e700a: clk_hw_register_gpio_mux.cold.6 (STB_LOCAL)
ffffffff815e6f80-ffffffff815e6fa4: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:176
Inline: False
```
**Symbols:**

```
ffffffff816013f9-ffffffff81601411: clk_hw_register_gpio_mux.cold.4 (STB_LOCAL)
ffffffff81601310-ffffffff81601334: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:211
Inline: False
```
**Symbols:**

```
ffffffff81633d41-ffffffff81633d59: clk_hw_register_gpio_mux.cold (STB_LOCAL)
ffffffff81633c50-ffffffff81633c74: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:211
Inline: False
```
**Symbols:**

```
ffffffff81655a74-ffffffff81655a8c: clk_hw_register_gpio_mux.cold (STB_LOCAL)
ffffffff81655980-ffffffff816559a4: clk_hw_register_gpio_mux (STB_GLOBAL)
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:187
Inline: True
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
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffff8000107c77c8)
Location: drivers/clk/clk-gpio.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffff8000107c77c8-ffff8000107c7858: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (c08f27b4)
Location: drivers/clk/clk-gpio.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
c08f27b4-c08f2810: clk_hw_register_gpio_mux (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffe0005145a6)
Location: drivers/clk/clk-gpio.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffe0005145a6-ffffffe00051461c: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:211
Inline: False
```
**Symbols:**

```
ffffffff8161bad4-ffffffff8161baec: clk_hw_register_gpio_mux.cold (STB_LOCAL)
ffffffff8161b9e0-ffffffff8161ba04: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:211
Inline: False
```
**Symbols:**

```
ffffffff81610004-ffffffff8161001c: clk_hw_register_gpio_mux.cold (STB_LOCAL)
ffffffff8160ff10-ffffffff8160ff34: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:211
Inline: False
```
**Symbols:**

```
ffffffff816498b4-ffffffff816498cc: clk_hw_register_gpio_mux.cold (STB_LOCAL)
ffffffff816497c0-ffffffff816497e4: clk_hw_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: drivers/clk/clk-gpio.c:211
Inline: False
```
**Symbols:**

```
ffffffff81663e44-ffffffff81663e5c: clk_hw_register_gpio_mux.cold (STB_LOCAL)
ffffffff81663d50-ffffffff81663d74: clk_hw_register_gpio_mux (STB_GLOBAL)
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
<code>dev, name, parent_names, num_parents, gpio, active_low, flags</code> ➡️ <code>dev, name, parent_names, num_parents, gpiod, flags</code>
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
