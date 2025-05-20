# Function: <code>gpio_set_func</code>

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
In drivers/mfd/wm8350-gpio.c (ffffffff81584cd1)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff815daddd)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff81607abd)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff8161b9a6)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff81684086)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff816c014a)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff816e151d)
Location: drivers/mfd/wm8350-gpio.c:50
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff8171ab8c)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff8173ee7c)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff817fc890)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff817fc890-ffffffff817fcae8: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff8180e310)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff8180e310-ffffffff8180e568: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff817f2af0)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff817f2af0-ffffffff817f2d93: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff8187b7c0)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff8187b7c0-ffffffff8187ba6f: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff819c40f0)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff819c40f0-ffffffff819c43a3: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff81b3ae50)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff81b3ae50-ffffffff81b3b103: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff81b8e2a0)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff81b8e2a0-ffffffff81b8e53c: gpio_set_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpio_set_func(struct wm8350 *wm8350, int gpio, int func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff81be21c0)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: False
Direct callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
```
**Symbols:**

```
ffffffff81be21c0-ffffffff81be245c: gpio_set_func (STB_LOCAL)
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
In drivers/mfd/wm8350-gpio.c (ffff80001093a210)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (c0a22498)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (c0000000009e15d8)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffe0005aed00)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm8350-gpio.c (ffffffff8173233c)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
In drivers/mfd/wm8350-gpio.c (ffffffff8174d77c)
Location: drivers/mfd/wm8350-gpio.c:45
Inline: True
Inline callers:
  - drivers/mfd/wm8350-gpio.c:wm8350_gpio_config
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
