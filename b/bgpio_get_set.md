# Function: <code>bgpio_get_set</code>

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
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
ffffffff817b2c00-ffffffff817b2cbc: bgpio_get_set (STB_LOCAL)
ffffffff81ea937c-ffffffff81ea93d3: bgpio_get_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
ffffffff818ccbb0-ffffffff818ccc6c: bgpio_get_set (STB_LOCAL)
ffffffff8208ea84-ffffffff8208eadb: bgpio_get_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
ffffffff8190fc20-ffffffff8190fcdc: bgpio_get_set (STB_LOCAL)
ffffffff8210ed76-ffffffff8210edcd: bgpio_get_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:131
Inline: False
```
**Symbols:**

```
ffffffff81957af0-ffffffff81957bac: bgpio_get_set (STB_LOCAL)
ffffffff821eca02-ffffffff821eca59: bgpio_get_set.cold (STB_LOCAL)
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
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc340)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
ffff8000106cc340-ffff8000106cc3cc: bgpio_get_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c08672e4)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
c08672e4-c0867340: bgpio_get_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000847d30)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
c000000000847d30-c000000000847df0: bgpio_get_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad418)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
ffffffe0004ad418-ffffffe0004ad48e: bgpio_get_set (STB_LOCAL)
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
int bgpio_get_set(struct gpio_chip *gc, unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569a80)
Location: drivers/gpio/gpio-mmio.c:132
Inline: False
```
**Symbols:**

```
ffffffff81569a80-ffffffff81569aee: bgpio_get_set (STB_LOCAL)
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
