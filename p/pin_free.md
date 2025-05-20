# Function: <code>pin_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8141faa0)
Location: drivers/pinctrl/pinmux.c:195
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
```
**Symbols:**

```
ffffffff8141faa0-ffffffff8141fb97: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814681d0)
Location: drivers/pinctrl/pinmux.c:195
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff814681d0-ffffffff814682cd: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814874b0)
Location: drivers/pinctrl/pinmux.c:195
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff814874b0-ffffffff814875ad: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81490d90)
Location: drivers/pinctrl/pinmux.c:182
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81490d90-ffffffff81490e79: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814ccf80)
Location: drivers/pinctrl/pinmux.c:182
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff814ccf80-ffffffff814cd075: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814fdf60)
Location: drivers/pinctrl/pinmux.c:182
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff814fdf60-ffffffff814fe053: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff815129d0)
Location: drivers/pinctrl/pinmux.c:181
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff815129d0-ffffffff81512ac3: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:180
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81541050-ffffffff81541128: pin_free (STB_LOCAL)
ffffffff81541e5d-ffffffff81541e8b: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81561e90-ffffffff81561f68: pin_free (STB_LOCAL)
ffffffff81562cfd-ffffffff81562d15: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81604470-ffffffff81604548: pin_free (STB_LOCAL)
ffffffff816052dd-ffffffff816052f5: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:206
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81628fe0-ffffffff816290b8: pin_free (STB_LOCAL)
ffffffff81bf52fc-ffffffff81bf5314: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:207
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff8160cb40-ffffffff8160cc18: pin_free (STB_LOCAL)
ffffffff81be7176-ffffffff81be718e: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:207
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff8167b680-ffffffff8167b758: pin_free (STB_LOCAL)
ffffffff81ce0597-ffffffff81ce05af: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:207
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81796e40-ffffffff81796f20: pin_free (STB_LOCAL)
ffffffff81ea6ce4-ffffffff81ea6cf9: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818ac750)
Location: drivers/pinctrl/pinmux.c:210
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff818ac750-ffffffff818ac845: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818ef6e0)
Location: drivers/pinctrl/pinmux.c:210
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff818ef6e0-ffffffff818ef7d5: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81936ea0)
Location: drivers/pinctrl/pinmux.c:208
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81936ea0-ffffffff81936f95: pin_free (STB_LOCAL)
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
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068ecb0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffff80001068ecb0-ffff80001068edb0: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c0830b58)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
c0830b58-c0830c68: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c000000000829ce0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
c000000000829ce0-c000000000829e54: pin_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049abbe)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffe00049abbe-ffffffe00049ac92: pin_free (STB_LOCAL)
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
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff8155a480-ffffffff8155a558: pin_free (STB_LOCAL)
ffffffff8155b2ed-ffffffff8155b305: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff8154a940-ffffffff8154aa18: pin_free (STB_LOCAL)
ffffffff8154b7ad-ffffffff8154b7c5: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff815561c0-ffffffff81556298: pin_free (STB_LOCAL)
ffffffff8155702d-ffffffff81557045: pin_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
const char *pin_free(struct pinctrl_dev *pctldev, int pin, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:204
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_free_gpio
```
**Symbols:**

```
ffffffff81570050-ffffffff81570128: pin_free (STB_LOCAL)
ffffffff81570ebd-ffffffff81570ed5: pin_free.cold (STB_LOCAL)
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
