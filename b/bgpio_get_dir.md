# Function: <code>bgpio_get_dir</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:364
Inline: False
```
**Symbols:**

```
ffffffff817b21c0-ffffffff817b227a: bgpio_get_dir (STB_LOCAL)
ffffffff81ea92c5-ffffffff81ea92da: bgpio_get_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:364
Inline: False
```
**Symbols:**

```
ffffffff818cc140-ffffffff818cc1fa: bgpio_get_dir (STB_LOCAL)
ffffffff8208e9cd-ffffffff8208e9e2: bgpio_get_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:364
Inline: False
```
**Symbols:**

```
ffffffff8190f1b0-ffffffff8190f26a: bgpio_get_dir (STB_LOCAL)
ffffffff8210ecbf-ffffffff8210ecd4: bgpio_get_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:363
Inline: False
```
**Symbols:**

```
ffffffff81956fb0-ffffffff8195706a: bgpio_get_dir (STB_LOCAL)
ffffffff821ec94b-ffffffff821ec960: bgpio_get_dir.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cce88)
Location: drivers/gpio/gpio-mmio.c:370
Inline: True
```
**Symbols:**

```
ffff8000106cce88-ffff8000106ccf8c: bgpio_get_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0868060)
Location: drivers/gpio/gpio-mmio.c:370
Inline: True
```
**Symbols:**

```
c0868060-c0868158: bgpio_get_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0000000008492a0)
Location: drivers/gpio/gpio-mmio.c:370
Inline: True
```
**Symbols:**

```
c0000000008492a0-c00000000084941c: bgpio_get_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ae0a4)
Location: drivers/gpio/gpio-mmio.c:370
Inline: True
```
**Symbols:**

```
ffffffe0004ae0a4-ffffffe0004ae176: bgpio_get_dir (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int bgpio_get_dir(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8156a9b0)
Location: drivers/gpio/gpio-mmio.c:370
Inline: True
```
**Symbols:**

```
ffffffff8156a9b0-ffffffff8156aaaf: bgpio_get_dir (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
