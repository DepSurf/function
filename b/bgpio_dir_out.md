# Function: <code>bgpio_dir_out</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff817b2280)
Location: drivers/gpio/gpio-mmio.c:386
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first
```
**Symbols:**

```
ffffffff817b2280-ffffffff817b231c: bgpio_dir_out.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cc210)
Location: drivers/gpio/gpio-mmio.c:386
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first
```
**Symbols:**

```
ffffffff818cc210-ffffffff818cc2ac: bgpio_dir_out.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190f280)
Location: drivers/gpio/gpio-mmio.c:386
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first
```
**Symbols:**

```
ffffffff8190f280-ffffffff8190f31c: bgpio_dir_out.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81957080)
Location: drivers/gpio/gpio-mmio.c:385
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_val_first
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out_dir_first
```
**Symbols:**

```
ffffffff81957080-ffffffff8195711c: bgpio_dir_out.isra.0 (STB_LOCAL)
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
int bgpio_dir_out(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cd228)
Location: drivers/gpio/gpio-mmio.c:384
Inline: False
```
**Symbols:**

```
ffff8000106cd228-ffff8000106cd34c: bgpio_dir_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bgpio_dir_out(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c086794c)
Location: drivers/gpio/gpio-mmio.c:384
Inline: False
```
**Symbols:**

```
c086794c-c08679f4: bgpio_dir_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bgpio_dir_out(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c000000000848700)
Location: drivers/gpio/gpio-mmio.c:384
Inline: False
```
**Symbols:**

```
c000000000848700-c000000000848800: bgpio_dir_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bgpio_dir_out(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004adaa0)
Location: drivers/gpio/gpio-mmio.c:384
Inline: False
```
**Symbols:**

```
ffffffe0004adaa0-ffffffe0004adb2e: bgpio_dir_out (STB_LOCAL)
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
int bgpio_dir_out(struct gpio_chip *gc, unsigned int gpio, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff81569ec0)
Location: drivers/gpio/gpio-mmio.c:384
Inline: False
```
**Symbols:**

```
ffffffff81569ec0-ffffffff81569f78: bgpio_dir_out (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
