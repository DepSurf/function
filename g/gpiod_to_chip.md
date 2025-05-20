# Function: <code>gpiod_to_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81423f40)
Location: drivers/gpio/gpiolib.c:119
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_direction
  - drivers/gpio/gpiolib.c:gpiod_hog
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
**Symbols:**

```
ffffffff81423f40-ffffffff81423f57: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814726b2)
Location: drivers/gpio/gpiolib.c:139
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
**Symbols:**

```
ffffffff8146d530-ffffffff8146d553: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814947d2)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
**Symbols:**

```
ffffffff8148f400-ffffffff8148f423: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149e1f1)
Location: drivers/gpio/gpiolib.c:143
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
**Symbols:**

```
ffffffff81498ec0-ffffffff81498ee3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dcd51)
Location: drivers/gpio/gpiolib.c:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff814d71b0-ffffffff814d71d3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150b135)
Location: drivers/gpio/gpiolib.c:171
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81506370-ffffffff81506393: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151fbb3)
Location: drivers/gpio/gpiolib.c:172
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff8151a820-ffffffff8151a843: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154dce9)
Location: drivers/gpio/gpiolib.c:172
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff815489c0-ffffffff815489e3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156eee9)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81569990-ffffffff815699b3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816133a9)
Location: drivers/gpio/gpiolib.c:175
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_ready_for_gpio_range
```
**Symbols:**

```
ffffffff8160c320-ffffffff8160c343: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81638272)
Location: drivers/gpio/gpiolib.c:172
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_ready_for_gpio_range
```
**Symbols:**

```
ffffffff816331d0-ffffffff816331f3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161bdb2)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81616eb0-ffffffff81616ed3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168b2de)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81686130-ffffffff81686153: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a8649)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff817a2a10-ffffffff817a2a3f: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c1051)
Location: drivers/gpio/gpiolib.c:175
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff818b9cf0-ffffffff818b9d1f: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81904034)
Location: drivers/gpio/gpiolib.c:192
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff818fcde0-ffffffff818fce0f: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194ba74)
Location: drivers/gpio/gpiolib.c:202
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
**Symbols:**

```
ffffffff81944400-ffffffff8194442f: gpiod_to_chip (STB_GLOBAL)
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
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c4e28)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffff8000106bd650-ffff8000106bd68c: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08630c8)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
c085ccd0-c085ccfc: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841980)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
c000000000838d70-c000000000838da8: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a949a)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffe0004a3eb8-ffffffe0004a3ee6: gpiod_to_chip (STB_GLOBAL)
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
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815646a9)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff8155f150-ffffffff8155f173: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815554f9)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff8154ffa0-ffffffff8154ffc3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81563219)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff8155dcc0-ffffffff8155dce3: gpiod_to_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiod_to_chip(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157d139)
Location: drivers/gpio/gpiolib.c:174
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_direction
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81577b50-ffffffff81577b73: gpiod_to_chip (STB_GLOBAL)
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
