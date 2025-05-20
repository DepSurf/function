# Function: <code>pin_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8141f7e0)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
```
**Symbols:**

```
ffffffff8141f7e0-ffffffff8141fa9e: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81467f70)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81467f70-ffffffff814681c5: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81487250)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81487250-ffffffff814874a5: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81490af0)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81490af0-ffffffff81490d8b: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814cccd0)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff814cccd0-ffffffff814ccf71: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814fdcc0)
Location: drivers/pinctrl/pinmux.c:83
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff814fdcc0-ffffffff814fdf57: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81512730)
Location: drivers/pinctrl/pinmux.c:82
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81512730-ffffffff815129c7: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:81
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81540e90-ffffffff81541050: pin_request (STB_LOCAL)
ffffffff81541d55-ffffffff81541e5d: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81561cd0-ffffffff81561e90: pin_request (STB_LOCAL)
ffffffff81562bf5-ffffffff81562cfd: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff816042b0-ffffffff81604470: pin_request (STB_LOCAL)
ffffffff816051d5-ffffffff816052dd: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:107
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81628e20-ffffffff81628fe0: pin_request (STB_LOCAL)
ffffffff81bf51f4-ffffffff81bf52fc: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:108
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff8160c980-ffffffff8160cb40: pin_request (STB_LOCAL)
ffffffff81be7071-ffffffff81be7176: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:108
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff8167b920-ffffffff8167bae3: pin_request (STB_LOCAL)
ffffffff81ce05af-ffffffff81ce06ea: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:108
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81797110-ffffffff817972d9: pin_request (STB_LOCAL)
ffffffff81ea6cf9-ffffffff81ea6e16: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff818aca90-ffffffff818acd39: pin_request (STB_LOCAL)
ffffffff8208def2-ffffffff8208df1c: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff818efc30-ffffffff818efee2: pin_request (STB_LOCAL)
ffffffff8210e1f2-ffffffff8210e21c: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff819373f0-ffffffff81937694: pin_request (STB_LOCAL)
ffffffff821ebe2f-ffffffff821ebe59: pin_request.cold (STB_LOCAL)
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
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068ea00)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffff80001068ea00-ffff80001068ecb0: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c08308b4)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
c08308b4-c0830b58: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c000000000829680)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
c000000000829680-c000000000829cd4: pin_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049a96a)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffe00049a96a-ffffffe00049abbe: pin_request (STB_LOCAL)
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
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff8155a2c0-ffffffff8155a480: pin_request (STB_LOCAL)
ffffffff8155b1e5-ffffffff8155b2ed: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff8154a780-ffffffff8154a940: pin_request (STB_LOCAL)
ffffffff8154b6a5-ffffffff8154b7ad: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff81556000-ffffffff815561c0: pin_request (STB_LOCAL)
ffffffff81556f25-ffffffff8155702d: pin_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pin_request(struct pinctrl_dev *pctldev, int pin, const char *owner, struct pinctrl_gpio_range *gpio_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
```
**Symbols:**

```
ffffffff8156fe90-ffffffff81570050: pin_request (STB_LOCAL)
ffffffff81570db5-ffffffff81570ebd: pin_request.cold (STB_LOCAL)
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
