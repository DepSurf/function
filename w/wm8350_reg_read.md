# Function: <code>wm8350_reg_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81584190)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81584190-ffffffff815841f9: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff815da270)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff815da270-ffffffff815da2d9: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81606f60)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81606f60-ffffffff81606fc9: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8161ae60)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff8161ae60-ffffffff8161aec9: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81683540)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81683540-ffffffff816835a9: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff816bf5d0)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff816bf5d0-ffffffff816bf63b: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff816e09a0)
Location: drivers/mfd/wm8350-core.c:79
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff816e09a0-ffffffff816e0a0b: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (0)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff8171a4e8-ffffffff8171a4ff: wm8350_reg_read.cold (STB_LOCAL)
ffffffff8171a0f0-ffffffff8171a14a: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (0)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff8173e7d8-ffffffff8173e7ef: wm8350_reg_read.cold (STB_LOCAL)
ffffffff8173e3e0-ffffffff8173e43a: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff817fc04b)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff817fc1d9-ffffffff817fc1f0: wm8350_reg_read.cold (STB_LOCAL)
ffffffff817fbd70-ffffffff817fbdca: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8180e0db)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81c1237d-ffffffff81c12394: wm8350_reg_read.cold (STB_LOCAL)
ffffffff8180de00-ffffffff8180de5a: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff817f28bd)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81c044fb-ffffffff81c04512: wm8350_reg_read.cold (STB_LOCAL)
ffffffff817f25e0-ffffffff817f263b: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8187b50d)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81d07641-ffffffff81d07658: wm8350_reg_read.cold (STB_LOCAL)
ffffffff8187b230-ffffffff8187b28b: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff819c3ded)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81ecff3c-ffffffff81ecff53: wm8350_reg_read.cold (STB_LOCAL)
ffffffff819c3ab0-ffffffff819c3b1c: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81b3a53d)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81b3a080-ffffffff81b3a0fb: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81b8d99b)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81b8d4e0-ffffffff81b8d55b: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81be18bb)
Location: drivers/mfd/wm8350-core.c:75
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81be1400-ffffffff81be147b: wm8350_reg_read (STB_GLOBAL)
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
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffff8000109396f8)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffff8000109396f8-ffff800010939780: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (c0a21a14)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
c0a21a14-c0a21a9c: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (c0000000009e07d0)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
c0000000009e07d0-c0000000009e0878: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffe0005ae2f6)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffe0005ae2f6-ffffffe0005ae34c: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (0)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff81731c98-ffffffff81731caf: wm8350_reg_read.cold (STB_LOCAL)
ffffffff817318a0-ffffffff817318fa: wm8350_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u16 wm8350_reg_read(struct wm8350 *wm8350, int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (0)
Location: drivers/mfd/wm8350-core.c:75
Inline: False
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/wm8350-irq.c:wm8350_irq
```
**Symbols:**

```
ffffffff8174d0d8-ffffffff8174d0ef: wm8350_reg_read.cold (STB_LOCAL)
ffffffff8174cce0-ffffffff8174cd3a: wm8350_reg_read (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
