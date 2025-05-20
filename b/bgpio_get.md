# Function: <code>bgpio_get</code>

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
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
ffffffff817b2ab0-ffffffff817b2b4d: bgpio_get (STB_LOCAL)
ffffffff81ea92da-ffffffff81ea9325: bgpio_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
ffffffff818cca40-ffffffff818ccadd: bgpio_get (STB_LOCAL)
ffffffff8208e9e2-ffffffff8208ea2d: bgpio_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
ffffffff8190fab0-ffffffff8190fb4d: bgpio_get (STB_LOCAL)
ffffffff8210ecd4-ffffffff8210ed1f: bgpio_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:166
Inline: False
```
**Symbols:**

```
ffffffff81957980-ffffffff81957a1d: bgpio_get (STB_LOCAL)
ffffffff821ec960-ffffffff821ec9ab: bgpio_get.cold (STB_LOCAL)
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
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc468)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
ffff8000106cc468-ffff8000106cc4dc: bgpio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c08673c8)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
c08673c8-c0867420: bgpio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000847ee0)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
c000000000847ee0-c000000000847f98: bgpio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad514)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
ffffffe0004ad514-ffffffe0004ad57a: bgpio_get (STB_LOCAL)
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
int bgpio_get(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569b70)
Location: drivers/gpio/gpio-mmio.c:167
Inline: False
```
**Symbols:**

```
ffffffff81569b70-ffffffff81569bcc: bgpio_get (STB_LOCAL)
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
