# Function: <code>gpiod_configure_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, enum gpiod_flags dflags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426090)
Location: drivers/gpio/gpiolib.c:2093
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_hog
```
**Symbols:**

```
ffffffff81426090-ffffffff814260e5: gpiod_configure_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81470400)
Location: drivers/gpio/gpiolib.c:3094
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81470400-ffffffff81470467: gpiod_configure_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81492780)
Location: drivers/gpio/gpiolib.c:3215
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81492780-ffffffff814927ea: gpiod_configure_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149dc30)
Location: drivers/gpio/gpiolib.c:3224
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff8149dc30-ffffffff8149dca4: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dc700)
Location: drivers/gpio/gpiolib.c:3557
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff814dc700-ffffffff814dc7f8: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3775
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff8150bee4-ffffffff8150bf14: gpiod_configure_flags.cold.51 (STB_LOCAL)
ffffffff8150ab00-ffffffff8150abde: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff81520e14-ffffffff81520e44: gpiod_configure_flags.cold.49 (STB_LOCAL)
ffffffff8151f5a0-ffffffff8151f67e: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4123
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff8154f1c5-ffffffff8154f236: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff8154d730-ffffffff8154d83f: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff815706c2-ffffffff81570733: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff8156e930-ffffffff8156ea3f: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4930
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff81614cad-ffffffff81614d1e: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff81612e20-ffffffff81612f72: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3754
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
**Symbols:**

```
ffffffff81bf6533-ffffffff81bf65b0: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff81637ce0-ffffffff81637e36: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3736
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
**Symbols:**

```
ffffffff81be83d9-ffffffff81be8456: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff8161b690-ffffffff8161b7e6: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3795
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
**Symbols:**

```
ffffffff81ce2086-ffffffff81ce2103: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff8168aba0-ffffffff8168acf3: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3923
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
```
**Symbols:**

```
ffffffff81ea8a98-ffffffff81ea8b15: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff817a7ed0-ffffffff817a801e: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c0540)
Location: drivers/gpio/gpiolib.c:4070
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
**Symbols:**

```
ffffffff818c0540-ffffffff818c0746: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81903510)
Location: drivers/gpio/gpiolib.c:4108
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
**Symbols:**

```
ffffffff81903510-ffffffff81903726: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194b0f0)
Location: drivers/gpio/gpiolib.c:4307
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
```
**Symbols:**

```
ffffffff8194b0f0-ffffffff8194b2f4: gpiod_configure_flags (STB_GLOBAL)
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
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c45e8)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffff8000106c45e8-ffff8000106c4804: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c086290c)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
```
**Symbols:**

```
c086290c-c0862ab4: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000840d70)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
```
**Symbols:**

```
c000000000840d70-c000000000841048: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a8e12)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
```
**Symbols:**

```
ffffffe0004a8e12-ffffffe0004a8f9c: gpiod_configure_flags (STB_GLOBAL)
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
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff81565e82-ffffffff81565ef3: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff815640f0-ffffffff815641ff: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff81556cd2-ffffffff81556d43: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff81554f40-ffffffff8155504f: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff815649f2-ffffffff81564a63: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff81562c60-ffffffff81562d6f: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiod_configure_flags(struct gpio_desc *desc, const char *con_id, long unsigned int lflags, enum gpiod_flags dflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4457
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
```
**Symbols:**

```
ffffffff8157e912-ffffffff8157e983: gpiod_configure_flags.cold (STB_LOCAL)
ffffffff8157cb80-ffffffff8157cc8f: gpiod_configure_flags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int lflags</code>
</li>
<li>
<b>Param reordered. </b>
<code>desc, con_id, dflags</code> ➡️ <code>desc, con_id, lflags, dflags</code>
</li>
</ul>
</details>
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
