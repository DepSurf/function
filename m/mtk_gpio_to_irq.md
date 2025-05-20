# Function: <code>mtk_gpio_to_irq</code>

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
int mtk_gpio_to_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8400)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:825
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba570)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:469
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc798)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:743
Inline: False
```
**Symbols:**

```
ffff8000106b8400-ffff8000106b8460: mtk_gpio_to_irq (STB_LOCAL)
ffff8000106ba570-ffff8000106ba5dc: mtk_gpio_to_irq (STB_LOCAL)
ffff8000106bc798-ffff8000106bc804: mtk_gpio_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_gpio_to_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085930c)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:825
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b24c)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:469
Inline: False
```
**Symbols:**

```
c085930c-c0859358: mtk_gpio_to_irq (STB_LOCAL)
c085b24c-c085b2ac: mtk_gpio_to_irq (STB_LOCAL)
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
