# Function: <code>gpiod_hog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814273c0)
Location: drivers/gpio/gpiolib.c:2281
Inline: False
```
**Symbols:**

```
ffffffff814273c0-ffffffff8142750d: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81472690)
Location: drivers/gpio/gpiolib.c:3287
Inline: False
```
**Symbols:**

```
ffffffff81472690-ffffffff814727fd: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814947b0)
Location: drivers/gpio/gpiolib.c:3408
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff814947b0-ffffffff8149491d: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149e1e0)
Location: drivers/gpio/gpiolib.c:3439
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8149e1e0-ffffffff8149e312: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dcd40)
Location: drivers/gpio/gpiolib.c:3788
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff814dcd40-ffffffff814dce72: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4066
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8150bf14-ffffffff8150bfc3: gpiod_hog.cold.52 (STB_LOCAL)
ffffffff8150b130-ffffffff8150b1ce: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4343
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81520e44-ffffffff81520ef3: gpiod_hog.cold.50 (STB_LOCAL)
ffffffff8151ff80-ffffffff81520020: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4436
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8154f2b7-ffffffff8154f338: gpiod_hog.cold (STB_LOCAL)
ffffffff8154e0e0-ffffffff8154e156: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff815707bf-ffffffff81570840: gpiod_hog.cold (STB_LOCAL)
ffffffff8156f2e0-ffffffff8156f356: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:5180
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
```
**Symbols:**

```
ffffffff81614d5f-ffffffff81614def: gpiod_hog.cold (STB_LOCAL)
ffffffff81613920-ffffffff81613995: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4002
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
```
**Symbols:**

```
ffffffff81bf65f1-ffffffff81bf6687: gpiod_hog.cold (STB_LOCAL)
ffffffff81638800-ffffffff81638883: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3981
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81be84de-ffffffff81be8574: gpiod_hog.cold (STB_LOCAL)
ffffffff8161c330-ffffffff8161c3ac: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4040
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81ce218b-ffffffff81ce2221: gpiod_hog.cold (STB_LOCAL)
ffffffff8168b850-ffffffff8168b8cc: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4166
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81ea8b9b-ffffffff81ea8c3d: gpiod_hog.cold (STB_LOCAL)
ffffffff817a8c20-ffffffff817a8c9c: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c13e0)
Location: drivers/gpio/gpiolib.c:4192
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff818c13e0-ffffffff818c151a: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81904350)
Location: drivers/gpio/gpiolib.c:4230
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81904350-ffffffff8190449e: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194bd80)
Location: drivers/gpio/gpiolib.c:4429
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff8194bd80-ffffffff8194bec1: gpiod_hog (STB_GLOBAL)
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
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c53a8)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffff8000106c53a8-ffff8000106c54dc: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08634d0)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c08634d0-c08635ec: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841f10)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c000000000841f10-c000000000842084: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a985e)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffffffe0004a985e-ffffffe0004a9960: gpiod_hog (STB_GLOBAL)
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
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81565f7f-ffffffff81566000: gpiod_hog.cold (STB_LOCAL)
ffffffff81564aa0-ffffffff81564b16: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81556dcf-ffffffff81556e50: gpiod_hog.cold (STB_LOCAL)
ffffffff815558f0-ffffffff81555966: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81564aef-ffffffff81564b70: gpiod_hog.cold (STB_LOCAL)
ffffffff81563610-ffffffff81563686: gpiod_hog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiod_hog(struct gpio_desc *desc, const char *name, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4701
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8157ea0f-ffffffff8157ea90: gpiod_hog.cold (STB_LOCAL)
ffffffff8157d530-ffffffff8157d5a6: gpiod_hog (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
