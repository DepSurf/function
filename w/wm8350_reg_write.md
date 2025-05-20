# Function: <code>wm8350_reg_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff815842e0)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff815842e0-ffffffff81584327: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff815da3c0)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff815da3c0-ffffffff815da407: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff816070b0)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff816070b0-ffffffff816070f7: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8161afb0)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff8161afb0-ffffffff8161aff7: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81683690)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81683690-ffffffff816836d7: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff816bf730)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff816bf730-ffffffff816bf780: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff816e0b00)
Location: drivers/mfd/wm8350-core.c:92
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff816e0b00-ffffffff816e0b50: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8171a50f)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff8171a4ff-ffffffff8171a51c: wm8350_reg_write.cold (STB_LOCAL)
ffffffff8171a170-ffffffff8171a1a3: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8173e7ff)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff8173e7ef-ffffffff8173e80c: wm8350_reg_write.cold (STB_LOCAL)
ffffffff8173e460-ffffffff8173e493: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff817fc065)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff817fc2b2-ffffffff817fc2cf: wm8350_reg_write.cold (STB_LOCAL)
ffffffff817fbe70-ffffffff817fbea3: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8180e0f5)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81c12456-ffffffff81c12473: wm8350_reg_write.cold (STB_LOCAL)
ffffffff8180df00-ffffffff8180df33: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff817f28d7)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81c045d4-ffffffff81c045f1: wm8350_reg_write.cold (STB_LOCAL)
ffffffff817f26e0-ffffffff817f2713: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8187b527)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81d0771a-ffffffff81d07737: wm8350_reg_write.cold (STB_LOCAL)
ffffffff8187b330-ffffffff8187b363: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff819c3e0e)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81ed0021-ffffffff81ed003e: wm8350_reg_write.cold (STB_LOCAL)
ffffffff819c3bf0-ffffffff819c3c2d: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81b3aa5b)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81b3a340-ffffffff81b3a3a8: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81b8dec6)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81b8d7a0-ffffffff81b8d808: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81be1de6)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
Direct callers:
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-gpio.c:gpio_set_func
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81be16c0-ffffffff81be1728: wm8350_reg_write (STB_GLOBAL)
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
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffff8000109397b0)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffff8000109397b0-ffff800010939818: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (c0a21ac0)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
c0a21ac0-c0a21b0c: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (c0000000009e08c0)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
c0000000009e08c0-c0000000009e0944: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffe0005ae37a)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffe0005ae37a-ffffffe0005ae3d4: wm8350_reg_write (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff81731cbf)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff81731caf-ffffffff81731ccc: wm8350_reg_write.cold (STB_LOCAL)
ffffffff81731920-ffffffff81731953: wm8350_reg_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int wm8350_reg_write(struct wm8350 *wm8350, int reg, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/wm8350-core.c (ffffffff8174d0ff)
Location: drivers/mfd/wm8350-core.c:88
Inline: True
Direct callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/wm8350-core.c:wm8350_reg_unlock
  - drivers/mfd/wm8350-core.c:wm8350_reg_lock
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
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
**Symbols:**

```
ffffffff8174d0ef-ffffffff8174d10c: wm8350_reg_write.cold (STB_LOCAL)
ffffffff8174cd60-ffffffff8174cd93: wm8350_reg_write (STB_GLOBAL)
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
