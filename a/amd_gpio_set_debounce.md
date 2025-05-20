# Function: <code>amd_gpio_set_debounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int amd_gpio_set_debounce(struct gpio_chip *gc, unsigned int offset, unsigned int debounce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81421af0)
Location: drivers/pinctrl/pinctrl-amd.c:118
Inline: False
```
**Symbols:**

```
ffffffff81421af0-ffffffff81421c01: amd_gpio_set_debounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int amd_gpio_set_debounce(struct gpio_chip *gc, unsigned int offset, unsigned int debounce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146a440)
Location: drivers/pinctrl/pinctrl-amd.c:102
Inline: False
```
**Symbols:**

```
ffffffff8146a440-ffffffff8146a53e: amd_gpio_set_debounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_gpio_set_debounce(struct gpio_chip *gc, unsigned int offset, unsigned int debounce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814895d0)
Location: drivers/pinctrl/pinctrl-amd.c:102
Inline: False
```
**Symbols:**

```
ffffffff814895d0-ffffffff814896ce: amd_gpio_set_debounce (STB_LOCAL)
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81492ff1)
Location: drivers/pinctrl/pinctrl-amd.c:107
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cf281)
Location: drivers/pinctrl/pinctrl-amd.c:107
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500415)
Location: drivers/pinctrl/pinctrl-amd.c:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81514e65)
Location: drivers/pinctrl/pinctrl-amd.c:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543045)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81563f55)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606485)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162adb5)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160ea95)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167d935)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799375)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818af455)
Location: drivers/pinctrl/pinctrl-amd.c:118
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2d30)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193a560)
Location: drivers/pinctrl/pinctrl-amd.c:119
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
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
In drivers/pinctrl/pinctrl-amd.c (ffff8000106931fc)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (c083485c)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (c0000000008300ac)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e29e)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155c545)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558285)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572115)
Location: drivers/pinctrl/pinctrl-amd.c:116
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
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
</ul>
