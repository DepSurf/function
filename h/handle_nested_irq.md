# Function: <code>handle_nested_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ddd60)
Location: kernel/irq/chip.c:330
Inline: False
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/tps65912-irq.c:tps65912_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff810ddd60-ffffffff810dde25: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e36a0)
Location: kernel/irq/chip.c:330
Inline: False
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff810e36a0-ffffffff810e376c: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9f30)
Location: kernel/irq/chip.c:329
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff810e9f30-ffffffff810e9ff0: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e95e0)
Location: kernel/irq/chip.c:431
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff810e95e0-ffffffff810e96ca: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1970)
Location: kernel/irq/chip.c:454
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff810f1970-ffffffff810f1a60: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f9b30)
Location: kernel/irq/chip.c:452
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff810f9b30-ffffffff810f9c20: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811052f0)
Location: kernel/irq/chip.c:452
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff811052f0-ffffffff811053df: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e640)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff8110e640-ffffffff8110e737: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a900)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff8111a900-ffffffff8111a9f7: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81126a00)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff81126a00-ffffffff81126af7: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122600)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff81122600-ffffffff811226f7: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122b60)
Location: kernel/irq/chip.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff81122b60-ffffffff81122c57: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143130)
Location: kernel/irq/chip.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff81143130-ffffffff81143225: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811669e0)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff811669e0-ffffffff81166acf: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119acc0)
Location: kernel/irq/chip.c:460
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff8119acc0-ffffffff8119adaf: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811aca20)
Location: kernel/irq/chip.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff811aca20-ffffffff811acb0f: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bc620)
Location: kernel/irq/chip.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff811bc620-ffffffff811bc70c: handle_nested_irq (STB_GLOBAL)
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
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017e618)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffff80001017e618-ffff80001017e810: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cecd0)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/tps65217.c:tps65217_irq_thread
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
c03cecd0-c03cee20: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d8e60)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
c0000000001d8e60-c0000000001d907c: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000116f04)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/tc3589x.c:tc3589x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/twl6030-irq.c:twl6030_irq_thread
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffe000116f04-ffffffe0001170ba: handle_nested_irq (STB_GLOBAL)
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
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112ee0)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
**Symbols:**

```
ffffffff81112ee0-ffffffff81112fd7: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81103c00)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
```
**Symbols:**

```
ffffffff81103c00-ffffffff81103ceb: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81110dd0)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff81110dd0-ffffffff81110ec7: handle_nested_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111c170)
Location: kernel/irq/chip.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/88pm860x-core.c:pm860x_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm8350-irq.c:wm8350_irq
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8925-core.c:max8925_tsc_irq
  - drivers/mfd/max8925-core.c:max8925_irq
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq
```
**Symbols:**

```
ffffffff8111c170-ffffffff8111c250: handle_nested_irq (STB_GLOBAL)
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
