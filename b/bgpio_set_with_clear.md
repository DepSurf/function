# Function: <code>bgpio_set_with_clear</code>

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
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:235
Inline: False
```
**Symbols:**

```
ffffffff817b2b50-ffffffff817b2bfc: bgpio_set_with_clear (STB_LOCAL)
ffffffff81ea9325-ffffffff81ea937c: bgpio_set_with_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:235
Inline: False
```
**Symbols:**

```
ffffffff818ccaf0-ffffffff818ccb9c: bgpio_set_with_clear (STB_LOCAL)
ffffffff8208ea2d-ffffffff8208ea84: bgpio_set_with_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:235
Inline: False
```
**Symbols:**

```
ffffffff8190fb60-ffffffff8190fc0c: bgpio_set_with_clear (STB_LOCAL)
ffffffff8210ed1f-ffffffff8210ed76: bgpio_set_with_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:234
Inline: False
```
**Symbols:**

```
ffffffff81957a30-ffffffff81957adc: bgpio_set_with_clear (STB_LOCAL)
ffffffff821ec9ab-ffffffff821eca02: bgpio_set_with_clear.cold (STB_LOCAL)
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
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc568)
Location: drivers/gpio/gpio-mmio.c:237
Inline: False
```
**Symbols:**

```
ffff8000106cc568-ffff8000106cc5ec: bgpio_set_with_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c086750c)
Location: drivers/gpio/gpio-mmio.c:237
Inline: False
```
**Symbols:**

```
c086750c-c0867558: bgpio_set_with_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000848120)
Location: drivers/gpio/gpio-mmio.c:237
Inline: False
```
**Symbols:**

```
c000000000848120-c0000000008481c0: bgpio_set_with_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad672)
Location: drivers/gpio/gpio-mmio.c:237
Inline: False
```
**Symbols:**

```
ffffffe0004ad672-ffffffe0004ad6d6: bgpio_set_with_clear (STB_LOCAL)
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
void bgpio_set_with_clear(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569cc0)
Location: drivers/gpio/gpio-mmio.c:237
Inline: False
```
**Symbols:**

```
ffffffff81569cc0-ffffffff81569d14: bgpio_set_with_clear (STB_LOCAL)
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
