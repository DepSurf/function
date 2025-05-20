# Function: <code>acpi_gpio_update_gpiod_flags</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, enum gpiod_flags update);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0896)
Location: drivers/gpio/gpiolib-acpi.c:465
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff814a00c0-ffffffff814a00f8: acpi_gpio_update_gpiod_flags.part.12 (STB_LOCAL)
ffffffff814a0760-ffffffff814a0779: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, enum gpiod_flags update);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814df2a0)
Location: drivers/gpio/gpiolib-acpi.c:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff814deb40-ffffffff814deb78: acpi_gpio_update_gpiod_flags.part.12 (STB_LOCAL)
ffffffff814df170-ffffffff814df189: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150e4d0)
Location: drivers/gpio/gpiolib-acpi.c:471
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8150e4d0-ffffffff8150e576: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81523b20)
Location: drivers/gpio/gpiolib-acpi.c:498
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81523b20-ffffffff81523bc6: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:517
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81552b8c-ffffffff81552ba6: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81552070-ffffffff8155210a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:587
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8157417c-ffffffff81574196: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff815736b0-ffffffff8157374a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff816186e4-ffffffff816186fe: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81617dd0-ffffffff81617e6a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:622
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81bf69c5-ffffffff81bf69de: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff8163e650-ffffffff8163e6e2: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:622
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81be88c5-ffffffff81be88df: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81622060-ffffffff816220fb: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:676
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81ce27af-ffffffff81ce27c9: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81691780-ffffffff81691818: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:661
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81ea9185-ffffffff81ea919b: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff817b0c30-ffffffff817b0cea: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
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
In drivers/gpio/gpiolib-acpi.c (ffffffff818c9d20)
Location: drivers/gpio/gpiolib-acpi.c:697
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff818c9d20-ffffffff818c9dfd: acpi_gpio_update_gpiod_flags.isra.0 (STB_LOCAL)
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8190cdc0)
Location: drivers/gpio/gpiolib-acpi.c:702
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8190cdc0-ffffffff8190ce88: acpi_gpio_update_gpiod_flags.isra.0 (STB_LOCAL)
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81954ac0)
Location: drivers/gpio/gpiolib-acpi.c:678
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81954ac0-ffffffff81954b88: acpi_gpio_update_gpiod_flags.isra.0 (STB_LOCAL)
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cb5e8)
Location: drivers/gpio/gpiolib-acpi.c:587
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffff8000106cb5e8-ffff8000106cb6b4: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
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
Location: drivers/gpio/gpiolib-acpi.h:66
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
Location: drivers/gpio/gpiolib-acpi.h:66
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
Location: drivers/gpio/gpiolib-acpi.h:66
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
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:587
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8156993c-ffffffff81569956: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81568e70-ffffffff81568f0a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:587
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8155a78c-ffffffff8155a7a6: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81559cc0-ffffffff81559d5a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:587
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff815684ac-ffffffff815684c6: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff815679e0-ffffffff81567a7a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_gpio_update_gpiod_flags(enum gpiod_flags *flags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:587
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff815823cc-ffffffff815823e6: acpi_gpio_update_gpiod_flags.cold (STB_LOCAL)
ffffffff81581900-ffffffff8158199a: acpi_gpio_update_gpiod_flags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_gpio_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>enum gpiod_flags update</code>
</li>
</ul>
</details>
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
