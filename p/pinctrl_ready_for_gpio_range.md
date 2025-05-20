# Function: <code>pinctrl_ready_for_gpio_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141d0bb)
Location: drivers/pinctrl/core.c:346
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8146575b)
Location: drivers/pinctrl/core.c:348
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81484a5b)
Location: drivers/pinctrl/core.c:348
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148e1bb)
Location: drivers/pinctrl/core.c:346
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814ca31b)
Location: drivers/pinctrl/core.c:346
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fb2d0)
Location: drivers/pinctrl/core.c:346
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8150fd30)
Location: drivers/pinctrl/core.c:345
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153e3f3)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8155f2c3)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pinctrl_ready_for_gpio_range(unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81601520)
Location: drivers/pinctrl/core.c:322
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81601520-ffffffff81601614: pinctrl_ready_for_gpio_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pinctrl_ready_for_gpio_range(unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81626380)
Location: drivers/pinctrl/core.c:323
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
**Symbols:**

```
ffffffff81626380-ffffffff81626474: pinctrl_ready_for_gpio_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81609ec1)
Location: drivers/pinctrl/core.c:323
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81678b41)
Location: drivers/pinctrl/core.c:323
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81793f2c)
Location: drivers/pinctrl/core.c:323
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818a916c)
Location: drivers/pinctrl/core.c:324
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ec05c)
Location: drivers/pinctrl/core.c:323
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81934779)
Location: drivers/pinctrl/core.c:335
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068b67c)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082da08)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c0000000008240a0)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000497c08)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815578b3)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81547d73)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815535f3)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156d483)
Location: drivers/pinctrl/core.c:321
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
