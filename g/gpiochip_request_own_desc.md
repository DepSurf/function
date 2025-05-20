# Function: <code>gpiochip_request_own_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814246b0)
Location: drivers/gpio/gpiolib.c:1049
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff814246b0-ffffffff81424710: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146dd60)
Location: drivers/gpio/gpiolib.c:2003
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8146dd60-ffffffff8146ddcb: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148fc20)
Location: drivers/gpio/gpiolib.c:2190
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8148fc20-ffffffff8148fc8b: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a2d0)
Location: drivers/gpio/gpiolib.c:2191
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8149a2d0-ffffffff8149a33b: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d85e0)
Location: drivers/gpio/gpiolib.c:2333
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff814d85e0-ffffffff814d864b: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81507b30)
Location: drivers/gpio/gpiolib.c:2447
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81507b30-ffffffff81507b9b: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f680)
Location: drivers/gpio/gpiolib.c:2477
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8151f680-ffffffff8151f74b: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2545
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8154f236-ffffffff8154f261: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff8154d840-ffffffff8154d8e7: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81570733-ffffffff8157075e: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff8156ea40-ffffffff8156eae7: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3255
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81614d1e-ffffffff81614d48: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff81612f80-ffffffff8161302a: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2064
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff81bf65b0-ffffffff81bf65da: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff81637e40-ffffffff81637eed: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2041
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff81be8456-ffffffff81be8480: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff8161b7f0-ffffffff8161b89d: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2060
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff81ce2103-ffffffff81ce212d: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff8168ad00-ffffffff8168adad: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2121
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff81ea8b15-ffffffff81ea8b40: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff817a8020-ffffffff817a80ed: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c0760)
Location: drivers/gpio/gpiolib.c:2191
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff818c0760-ffffffff818c087f: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81903740)
Location: drivers/gpio/gpiolib.c:2232
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff81903740-ffffffff8190385f: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *gc, unsigned int hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194b310)
Location: drivers/gpio/gpiolib.c:2426
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_request_own_gpiod
```
**Symbols:**

```
ffffffff8194b310-ffffffff8194b443: gpiochip_request_own_desc (STB_GLOBAL)
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
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c4808)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_request
```
**Symbols:**

```
ffff8000106c4808-ffff8000106c4900: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0862ab4)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_request
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
```
**Symbols:**

```
c0862ab4-c0862b80: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841050)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
```
**Symbols:**

```
c000000000841050-c00000000084119c: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a8f9c)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
```
**Symbols:**

```
ffffffe0004a8f9c-ffffffe0004a9064: gpiochip_request_own_desc (STB_GLOBAL)
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
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81565ef3-ffffffff81565f1e: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff81564200-ffffffff815642a7: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81556d43-ffffffff81556d6e: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff81555050-ffffffff815550f7: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81564a63-ffffffff81564a8e: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff81562d70-ffffffff81562e17: gpiochip_request_own_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpiochip_request_own_desc(struct gpio_chip *chip, u16 hwnum, const char *label, enum gpio_lookup_flags lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2877
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8157e983-ffffffff8157e9ae: gpiochip_request_own_desc.cold (STB_LOCAL)
ffffffff8157cc90-ffffffff8157cd37: gpiochip_request_own_desc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum gpiod_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum gpio_lookup_flags lflags</code>
</li>
<li>
<b>Param added. </b>
<code>enum gpiod_flags dflags</code>
</li>
<li>
<b>Param removed. </b>
<code>enum gpiod_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *chip</code>
</li>
<li>
<b>Param type changed. </b>
<code>u16 hwnum</code> ➡️ <code>unsigned int hwnum</code>
</li>
</ul>
</details>
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
