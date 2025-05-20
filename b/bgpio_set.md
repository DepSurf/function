# Function: <code>bgpio_set</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b2090)
Location: drivers/gpio/gpio-mmio.c:218
Inline: False
```
**Symbols:**

```
ffffffff817b2090-ffffffff817b2119: bgpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cbff0)
Location: drivers/gpio/gpio-mmio.c:218
Inline: False
```
**Symbols:**

```
ffffffff818cbff0-ffffffff818cc079: bgpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190f060)
Location: drivers/gpio/gpio-mmio.c:218
Inline: False
```
**Symbols:**

```
ffffffff8190f060-ffffffff8190f0e9: bgpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81956e60)
Location: drivers/gpio/gpio-mmio.c:217
Inline: False
```
**Symbols:**

```
ffffffff81956e60-ffffffff81956ee9: bgpio_set (STB_LOCAL)
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
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cd660)
Location: drivers/gpio/gpio-mmio.c:220
Inline: False
```
**Symbols:**

```
ffff8000106cd660-ffff8000106cd758: bgpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0867490)
Location: drivers/gpio/gpio-mmio.c:220
Inline: False
```
**Symbols:**

```
c0867490-c086750c: bgpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000848040)
Location: drivers/gpio/gpio-mmio.c:220
Inline: False
```
**Symbols:**

```
c000000000848040-c000000000848118: bgpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad5e8)
Location: drivers/gpio/gpio-mmio.c:220
Inline: False
```
**Symbols:**

```
ffffffe0004ad5e8-ffffffe0004ad672: bgpio_set (STB_LOCAL)
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
void bgpio_set(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569c20)
Location: drivers/gpio/gpio-mmio.c:220
Inline: False
```
**Symbols:**

```
ffffffff81569c20-ffffffff81569cb9: bgpio_set (STB_LOCAL)
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
