# Function: <code>sx150x_gpio_direction_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *gc, unsigned int offset, int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-sx150x.c (ffffffff8142b7a0)
Location: drivers/gpio/gpio-sx150x.c:341
Inline: True
```
**Symbols:**

```
ffffffff8142b7a0-ffffffff8142b849: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *gc, unsigned int offset, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-sx150x.c (ffffffff814760f0)
Location: drivers/gpio/gpio-sx150x.c:449
Inline: False
```
**Symbols:**

```
ffffffff814760f0-ffffffff8147619a: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148aaa0)
Location: drivers/pinctrl/pinctrl-sx150x.c:511
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff8148aaa0-ffffffff8148ab6f: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81494380)
Location: drivers/pinctrl/pinctrl-sx150x.c:476
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81494380-ffffffff81494444: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0620)
Location: drivers/pinctrl/pinctrl-sx150x.c:476
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff814d0620-ffffffff814d06e4: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501f30)
Location: drivers/pinctrl/pinctrl-sx150x.c:476
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81501f30-ffffffff81501ffa: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81516a20)
Location: drivers/pinctrl/pinctrl-sx150x.c:476
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81516a20-ffffffff81516aea: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81544bd0)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81544bd0-ffffffff81544c8c: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81565ab0)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81565ab0-ffffffff81565b6c: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff816081c0)
Location: drivers/pinctrl/pinctrl-sx150x.c:471
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff816081c0-ffffffff816082a5: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162c9c0)
Location: drivers/pinctrl/pinctrl-sx150x.c:471
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff8162c9c0-ffffffff8162caa6: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff816106a0)
Location: drivers/pinctrl/pinctrl-sx150x.c:470
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff816106a0-ffffffff8161078a: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:470
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff8167f770-ffffffff8167f857: sx150x_gpio_direction_output (STB_LOCAL)
ffffffff81ce0e1b-ffffffff81ce0e34: sx150x_gpio_direction_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:470
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff8179b470-ffffffff8179b577: sx150x_gpio_direction_output (STB_LOCAL)
ffffffff81ea7532-ffffffff81ea754b: sx150x_gpio_direction_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:470
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff818b1cc0-ffffffff818b1dc7: sx150x_gpio_direction_output (STB_LOCAL)
ffffffff8208e200-ffffffff8208e219: sx150x_gpio_direction_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:469
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff818f4cf0-ffffffff818f4df7: sx150x_gpio_direction_output (STB_LOCAL)
ffffffff8210e4da-ffffffff8210e4f3: sx150x_gpio_direction_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff8193c500-ffffffff8193c607: sx150x_gpio_direction_output (STB_LOCAL)
ffffffff821ec117-ffffffff821ec130: sx150x_gpio_direction_output.cold (STB_LOCAL)
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
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069e8f8)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffff80001069e8f8-ffff80001069e9d0: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (c0841174)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
c0841174-c0841218: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (c0000000008368f0)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
c0000000008368f0-c0000000008369e4: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a26f0)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffe0004a26f0-ffffffe0004a2796: sx150x_gpio_direction_output (STB_LOCAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559de0)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81559de0-ffffffff81559e9c: sx150x_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sx150x_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573c70)
Location: drivers/pinctrl/pinctrl-sx150x.c:468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set
```
**Symbols:**

```
ffffffff81573c70-ffffffff81573d2c: sx150x_gpio_direction_output (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *chip</code>
</li>
<li>
<b>Param added. </b>
<code>int value</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>int val</code>
</li>
</ul>
</details>
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
