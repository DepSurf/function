# Function: <code>gpiochip_line_is_valid</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815066a5)
Location: drivers/gpio/gpiolib.c:389
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
```
**Symbols:**

```
ffffffff81506670-ffffffff81506696: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151c27e)
Location: drivers/gpio/gpiolib.c:398
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8151ac70-ffffffff8151ac96: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154a55f)
Location: drivers/gpio/gpiolib.c:398
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81549000-ffffffff81549027: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a3ef)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8156a080-ffffffff8156a0a7: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161049f)
Location: drivers/gpio/gpiolib.c:418
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8160f170-ffffffff8160f197: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8163671f)
Location: drivers/gpio/gpiolib.c:463
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff81635aa0-ffffffff81635ac7: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619d7b)
Location: drivers/gpio/gpiolib.c:461
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff816190d0-ffffffff816190f7: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168905b)
Location: drivers/gpio/gpiolib.c:483
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81688390-ffffffff816883b7: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a645d)
Location: drivers/gpio/gpiolib.c:484
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff817a2f70-ffffffff817a2fab: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ba3b0)
Location: drivers/gpio/gpiolib.c:540
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff818ba3b0-ffffffff818ba3eb: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fd4b0)
Location: drivers/gpio/gpiolib.c:567
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff818fd4b0-ffffffff818fd4eb: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81944ab0)
Location: drivers/gpio/gpiolib.c:646
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81944ab0-ffffffff81944aeb: gpiochip_line_is_valid (STB_GLOBAL)
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
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c1948)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request
```
**Symbols:**

```
ffff8000106bda38-ffff8000106bda98: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085ec54)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request
```
**Symbols:**

```
c085d3f8-c085d444: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000839f88)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
c000000000839940-c000000000839984: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a494e)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffe0004a451c-ffffffe0004a4574: gpiochip_line_is_valid (STB_GLOBAL)
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
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fbaf)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8155f840-ffffffff8155f867: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815509ff)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81550690-ffffffff815506b7: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e71f)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8155e3b0-ffffffff8155e3d7: gpiochip_line_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip *gpiochip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815785af)
Location: drivers/gpio/gpiolib.c:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81578240-ffffffff81578267: gpiochip_line_is_valid (STB_GLOBAL)
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
