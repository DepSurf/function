# Function: <code>mtk_gpio_direction_output</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int mtk_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b86d8)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:785
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba5e0)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:461
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc808)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:735
Inline: False
```
**Symbols:**

```
ffff8000106b86d8-ffff8000106b8728: mtk_gpio_direction_output (STB_LOCAL)
ffff8000106ba5e0-ffff8000106ba630: mtk_gpio_direction_output (STB_LOCAL)
ffff8000106bc808-ffff8000106bc858: mtk_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_gpio_direction_output(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c0859590)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:785
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b2ac)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:461
Inline: False
```
**Symbols:**

```
c0859590-c08595c0: mtk_gpio_direction_output (STB_LOCAL)
c085b2ac-c085b2dc: mtk_gpio_direction_output (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
