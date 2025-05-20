# Function: <code>devprop_gpiochip_set_names</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffffffff81494b50)
Location: drivers/gpio/gpiolib-devprop.c:28
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81494b50-ffffffff81494c4d: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffffffff8149e540)
Location: drivers/gpio/gpiolib-devprop.c:28
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8149e540-ffffffff8149e646: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffffffff814dd0a0)
Location: drivers/gpio/gpiolib-devprop.c:29
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff814dd0a0-ffffffff814dd187: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffffffff8150c280)
Location: drivers/gpio/gpiolib-devprop.c:29
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8150c280-ffffffff8150c359: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffffffff815218f0)
Location: drivers/gpio/gpiolib-devprop.c:26
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff815218f0-ffffffff815219bc: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8154fec9-ffffffff8154fee6: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff8154fe10-ffffffff8154fec9: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81571379-ffffffff81571396: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff815712c0-ffffffff81571379: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff816158c5-ffffffff81615901: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff81615810-ffffffff816158c5: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81638ebd)
Location: drivers/gpio/gpiolib.c:371
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161cac8)
Location: drivers/gpio/gpiolib.c:373
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devprop_gpiochip_set_names(struct gpio_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:373
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81688a80-ffffffff81688b98: devprop_gpiochip_set_names (STB_LOCAL)
ffffffff81ce171f-ffffffff81ce1760: devprop_gpiochip_set_names.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a92d9)
Location: drivers/gpio/gpiolib.c:366
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c1ca2)
Location: drivers/gpio/gpiolib.c:367
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
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
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffff8000106c75e8)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffff8000106c75e8-ffff8000106c76bc: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (c0864ebc)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c0864ebc-c0864f94: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (c000000000844180)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c000000000844180-c0000000008442fc: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (ffffffe0004aaf82)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffffffe0004aaf82-ffffffe0004ab070: devprop_gpiochip_set_names (STB_GLOBAL)
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
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81566b39-ffffffff81566b56: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff81566a80-ffffffff81566b39: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81557989-ffffffff815579a6: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff815578d0-ffffffff81557989: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff815656a9-ffffffff815656c6: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff815655f0-ffffffff815656a9: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void devprop_gpiochip_set_names(struct gpio_chip *chip, const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-devprop.c (0)
Location: drivers/gpio/gpiolib-devprop.c:27
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8157f5c9-ffffffff8157f5e6: devprop_gpiochip_set_names.cold (STB_LOCAL)
ffffffff8157f510-ffffffff8157f5c9: devprop_gpiochip_set_names (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
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
