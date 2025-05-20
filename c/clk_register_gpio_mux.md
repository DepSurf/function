# Function: <code>clk_register_gpio_mux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816eb180)
Location: drivers/clk/clk-gpio.c:190
Inline: False
```
**Symbols:**

```
ffffffff816eb180-ffffffff816eb1c8: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8174fc30)
Location: drivers/clk/clk-gpio.c:220
Inline: True
```
**Symbols:**

```
ffffffff8174fc30-ffffffff8174fc5f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815384a0)
Location: drivers/clk/clk-gpio.c:220
Inline: True
```
**Symbols:**

```
ffffffff815384a0-ffffffff815384cf: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8154b750)
Location: drivers/clk/clk-gpio.c:220
Inline: True
```
**Symbols:**

```
ffffffff8154b750-ffffffff8154b777: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815aed70)
Location: drivers/clk/clk-gpio.c:193
Inline: True
```
**Symbols:**

```
ffffffff815aed70-ffffffff815aed8f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815e6fb0)
Location: drivers/clk/clk-gpio.c:193
Inline: True
```
**Symbols:**

```
ffffffff815e6fb0-ffffffff815e6fcf: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81601340)
Location: drivers/clk/clk-gpio.c:190
Inline: True
```
**Symbols:**

```
ffffffff81601340-ffffffff8160135f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81633c80)
Location: drivers/clk/clk-gpio.c:225
Inline: True
```
**Symbols:**

```
ffffffff81633c80-ffffffff81633c9f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816559b0)
Location: drivers/clk/clk-gpio.c:225
Inline: True
```
**Symbols:**

```
ffffffff816559b0-ffffffff816559cf: clk_register_gpio_mux (STB_GLOBAL)
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
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffff8000107c79fc)
Location: drivers/clk/clk-gpio.c:225
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffff8000107c7858-ffff8000107c78c8: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (c08f2960)
Location: drivers/clk/clk-gpio.c:225
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
c08f2810-c08f284c: clk_register_gpio_mux (STB_GLOBAL)
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
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffe00051478c)
Location: drivers/clk/clk-gpio.c:225
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffe00051461c-ffffffe000514676: clk_register_gpio_mux (STB_GLOBAL)
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
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8161ba10)
Location: drivers/clk/clk-gpio.c:225
Inline: True
```
**Symbols:**

```
ffffffff8161ba10-ffffffff8161ba2f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8160ff40)
Location: drivers/clk/clk-gpio.c:225
Inline: True
```
**Symbols:**

```
ffffffff8160ff40-ffffffff8160ff5f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816497f0)
Location: drivers/clk/clk-gpio.c:225
Inline: True
```
**Symbols:**

```
ffffffff816497f0-ffffffff8164980f: clk_register_gpio_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_gpio_mux(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81663d80)
Location: drivers/clk/clk-gpio.c:225
Inline: True
```
**Symbols:**

```
ffffffff81663d80-ffffffff81663d9f: clk_register_gpio_mux (STB_GLOBAL)
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
