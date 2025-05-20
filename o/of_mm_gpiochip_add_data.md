# Function: <code>of_mm_gpiochip_add_data</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_mm_gpiochip_add_data(struct device_node *np, struct of_mm_gpio_chip *mm_gc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c76c0)
Location: drivers/gpio/gpiolib-of.c:717
Inline: False
```
**Symbols:**

```
ffff8000106c76c0-ffff8000106c7798: of_mm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_mm_gpiochip_add_data(struct device_node *np, struct of_mm_gpio_chip *mm_gc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0864f94)
Location: drivers/gpio/gpiolib-of.c:717
Inline: False
Direct callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_probe
```
**Symbols:**

```
c0864f94-c0865068: of_mm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_mm_gpiochip_add_data(struct device_node *np, struct of_mm_gpio_chip *mm_gc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c000000000844300)
Location: drivers/gpio/gpiolib-of.c:717
Inline: False
```
**Symbols:**

```
c000000000844300-c000000000844424: of_mm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_mm_gpiochip_add_data(struct device_node *np, struct of_mm_gpio_chip *mm_gc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab070)
Location: drivers/gpio/gpiolib-of.c:717
Inline: False
```
**Symbols:**

```
ffffffe0004ab070-ffffffe0004ab128: of_mm_gpiochip_add_data (STB_GLOBAL)
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
