# Function: <code>acpi_gpiochip_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81429560)
Location: drivers/gpio/gpiolib-acpi.c:784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add
```
**Symbols:**

```
ffffffff81429560-ffffffff8142969e: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474920)
Location: drivers/gpio/gpiolib-acpi.c:808
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
**Symbols:**

```
ffffffff81474920-ffffffff81474a86: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81496df0)
Location: drivers/gpio/gpiolib-acpi.c:934
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
**Symbols:**

```
ffffffff81496df0-ffffffff8149710b: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0a90)
Location: drivers/gpio/gpiolib-acpi.c:1046
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
**Symbols:**

```
ffffffff814a0a90-ffffffff814a0da6: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814df4a0)
Location: drivers/gpio/gpiolib-acpi.c:975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff814df4a0-ffffffff814df79d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150e840)
Location: drivers/gpio/gpiolib-acpi.c:1030
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8150e840-ffffffff8150eb4d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81523e90)
Location: drivers/gpio/gpiolib-acpi.c:1052
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81523e90-ffffffff815241ac: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1106
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81552ba6-ffffffff81552c0d: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff81552440-ffffffff8155270d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81574196-ffffffff815741fd: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff81573a80-ffffffff81573d4d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1193
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff816186fe-ffffffff81618745: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff816181a0-ffffffff81618310: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1233
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81bf69de-ffffffff81bf6a25: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff8163ebc0-ffffffff8163ed09: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1233
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81be88df-ffffffff81be8926: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff816225d0-ffffffff81622717: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1295
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81ce27fa-ffffffff81ce2842: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff81691d60-ffffffff81691e95: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1280
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81ea91d9-ffffffff81ea9220: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff817b12f0-ffffffff817b144f: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff818cacf0)
Location: drivers/gpio/gpiolib-acpi.c:1330
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff818cacf0-ffffffff818cae89: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190de00)
Location: drivers/gpio/gpiolib-acpi.c:1332
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8190de00-ffffffff8190df99: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81955b60)
Location: drivers/gpio/gpiolib-acpi.c:1309
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81955b60-ffffffff81955d28: acpi_gpiochip_add (STB_GLOBAL)
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
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cba68)
Location: drivers/gpio/gpiolib-acpi.c:1186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffff8000106cba68-ffff8000106cbdc8: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-acpi.h:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-acpi.h:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-acpi.h:56
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81569956-ffffffff815699bd: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff81569240-ffffffff8156950d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8155a7a6-ffffffff8155a80d: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff8155a090-ffffffff8155a35d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff815684c6-ffffffff8156852d: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff81567db0-ffffffff8156807d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_add(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff815823e6-ffffffff8158244d: acpi_gpiochip_add.cold (STB_LOCAL)
ffffffff81581cd0-ffffffff81581f9d: acpi_gpiochip_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
