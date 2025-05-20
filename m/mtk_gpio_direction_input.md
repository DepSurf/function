# Function: <code>mtk_gpio_direction_input</code>

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
int mtk_gpio_direction_input(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8728)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:779
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba630)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:456
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc858)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:730
Inline: False
```
**Symbols:**

```
ffff8000106b8728-ffff8000106b875c: mtk_gpio_direction_input (STB_LOCAL)
ffff8000106ba630-ffff8000106ba664: mtk_gpio_direction_input (STB_LOCAL)
ffff8000106bc858-ffff8000106bc88c: mtk_gpio_direction_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_gpio_direction_input(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c08595c0)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:779
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b2dc)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:456
Inline: False
```
**Symbols:**

```
c08595c0-c08595e4: mtk_gpio_direction_input (STB_LOCAL)
c085b2dc-c085b300: mtk_gpio_direction_input (STB_LOCAL)
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
