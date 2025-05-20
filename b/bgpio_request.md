# Function: <code>bgpio_request</code>

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
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b1b00)
Location: drivers/gpio/gpio-mmio.c:564
Inline: False
```
**Symbols:**

```
ffffffff817b1b00-ffffffff817b1b23: bgpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cb9e0)
Location: drivers/gpio/gpio-mmio.c:564
Inline: False
```
**Symbols:**

```
ffffffff818cb9e0-ffffffff818cba03: bgpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190ea50)
Location: drivers/gpio/gpio-mmio.c:564
Inline: False
```
**Symbols:**

```
ffffffff8190ea50-ffffffff8190ea73: bgpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff819567c0)
Location: drivers/gpio/gpio-mmio.c:563
Inline: False
```
**Symbols:**

```
ffffffff819567c0-ffffffff819567e3: bgpio_request (STB_LOCAL)
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
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc840)
Location: drivers/gpio/gpio-mmio.c:547
Inline: False
```
**Symbols:**

```
ffff8000106cc840-ffff8000106cc878: bgpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c08679f4)
Location: drivers/gpio/gpio-mmio.c:547
Inline: False
```
**Symbols:**

```
c08679f4-c0867a1c: bgpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000848800)
Location: drivers/gpio/gpio-mmio.c:547
Inline: False
```
**Symbols:**

```
c000000000848800-c000000000848828: bgpio_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004adb2e)
Location: drivers/gpio/gpio-mmio.c:547
Inline: False
```
**Symbols:**

```
ffffffe0004adb2e-ffffffe0004adb62: bgpio_request (STB_LOCAL)
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
int bgpio_request(struct gpio_chip *chip, unsigned int gpio_pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569f80)
Location: drivers/gpio/gpio-mmio.c:547
Inline: False
```
**Symbols:**

```
ffffffff81569f80-ffffffff81569f9b: bgpio_request (STB_LOCAL)
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
