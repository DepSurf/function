# Function: <code>pinmux_can_be_used_for_gpio</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81562470)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff81562470-ffffffff815624c3: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81604a50)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff81604a50-ffffffff81604aa9: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff816295b0)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff816295b0-ffffffff81629609: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8160d2f0)
Location: drivers/pinctrl/pinmux.c:84
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff8160d2f0-ffffffff8160d349: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:84
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff81ce0872-ffffffff81ce08c1: pinmux_can_be_used_for_gpio.cold (STB_LOCAL)
ffffffff8167c030-ffffffff8167c0b6: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:84
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff81ea6fa2-ffffffff81ea6ff1: pinmux_can_be_used_for_gpio.cold (STB_LOCAL)
ffffffff81797860-ffffffff817978e7: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff8208dfb4-ffffffff8208e003: pinmux_can_be_used_for_gpio.cold (STB_LOCAL)
ffffffff818ad400-ffffffff818ad487: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff8210e2a9-ffffffff8210e2f8: pinmux_can_be_used_for_gpio.cold (STB_LOCAL)
ffffffff818f0340-ffffffff818f03c7: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff821ebee6-ffffffff821ebf35: pinmux_can_be_used_for_gpio.cold (STB_LOCAL)
ffffffff81937af0-ffffffff81937b77: pinmux_can_be_used_for_gpio (STB_GLOBAL)
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
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068f548)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffff80001068f548-ffff80001068f5c8: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c08313a0)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
c08313a0-c0831414: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c00000000082aa10)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
c00000000082aa10-c00000000082aab8: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049b2f6)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffe00049b2f6-ffffffe00049b35a: pinmux_can_be_used_for_gpio (STB_GLOBAL)
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
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8155aa60)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff8155aa60-ffffffff8155aab3: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8154af20)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff8154af20-ffffffff8154af73: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff815567a0)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff815567a0-ffffffff815567f3: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pinmux_can_be_used_for_gpio(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81570630)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_can_use_line
```
**Symbols:**

```
ffffffff81570630-ffffffff81570683: pinmux_can_be_used_for_gpio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
