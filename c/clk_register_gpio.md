# Function: <code>clk_register_gpio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816eaf00)
Location: drivers/clk/clk-gpio.c:97
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
  - drivers/clk/clk-gpio.c:clk_register_gpio_mux
```
**Symbols:**

```
ffffffff816eaf00-ffffffff816eb125: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8174f950)
Location: drivers/clk/clk-gpio.c:97
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff8174f950-ffffffff8174fb89: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815381c0)
Location: drivers/clk/clk-gpio.c:97
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff815381c0-ffffffff815383f9: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8154b460)
Location: drivers/clk/clk-gpio.c:97
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff8154b460-ffffffff8154b6b3: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815aea50)
Location: drivers/clk/clk-gpio.c:95
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff815aea50-ffffffff815aebc1: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff815e6cb0)
Location: drivers/clk/clk-gpio.c:95
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff815e6cb0-ffffffff815e6e21: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816010e0)
Location: drivers/clk/clk-gpio.c:92
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_register_gpio_gate
```
**Symbols:**

```
ffffffff816010e0-ffffffff81601251: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81633a50)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff81633a50-ffffffff81633ba2: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81655780)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff81655780-ffffffff816558d2: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81705890)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81705890-ffffffff8170598a: clk_register_gpio.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81722b80)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81722b80-ffffffff81722c7a: clk_register_gpio.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk-gpio.c (ffffffff81703e20)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81703e20-ffffffff81703f18: clk_register_gpio.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk-gpio.c (ffffffff8177ec20)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff8177ec20-ffffffff8177ed18: clk_register_gpio.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk-gpio.c (ffffffff818b5b10)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff818b5b10-ffffffff818b5c18: clk_register_gpio.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk-gpio.c (ffffffff81a02bc0)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81a02bc0-ffffffff81a02cc8: clk_register_gpio.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk-gpio.c (ffffffff81a4ba10)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81a4ba10-ffffffff81a4bb18: clk_register_gpio.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81a97660)
Location: drivers/clk/clk-gpio.c:139
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffff81a97660-ffffffff81a97768: clk_register_gpio.constprop.0 (STB_LOCAL)
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
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffff8000107c7598)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffff8000107c7598-ffff8000107c76e0: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (c08f25ac)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
c08f25ac-c08f2704: clk_register_gpio (STB_LOCAL)
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
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffe0005143c4)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffe0005143c4-ffffffe0005144dc: clk_register_gpio (STB_LOCAL)
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
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8161b7e0)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff8161b7e0-ffffffff8161b932: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff8160fd10)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff8160fd10-ffffffff8160fe62: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff816495c0)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff816495c0-ffffffff81649712: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_hw *clk_register_gpio(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, struct gpio_desc *gpiod, long unsigned int flags, const struct clk_ops *clk_gpio_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (ffffffff81663b50)
Location: drivers/clk/clk-gpio.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff81663b50-ffffffff81663ca2: clk_register_gpio (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct clk *</code> ➡️ <code>struct clk_hw *</code>
</li>
</ul>
</details>
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
<code>dev, name, parent_names, num_parents, gpio, active_low, flags, clk_gpio_ops</code> ➡️ <code>dev, name, parent_names, num_parents, gpiod, flags, clk_gpio_ops</code>
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
