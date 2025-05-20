# Function: <code>acpi_gpio_in_ignore_list</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8157265d)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *controller_in, int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81616a20-ffffffff81616b1d: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff816185cf-ffffffff816185ee: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *controller_in, int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:270
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8163d350-ffffffff8163d44d: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff81bf68af-ffffffff81bf68ce: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *controller_in, int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:270
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81620eb0-ffffffff81620fad: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff81be87fa-ffffffff81be8819: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *controller_in, int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:324
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81690560-ffffffff81690668: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff81ce25dc-ffffffff81ce2610: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *controller_in, unsigned int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:320
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff817af950-ffffffff817afa8d: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff81ea8fd6-ffffffff81ea8fea: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *ignore_list, const char *controller_in, unsigned int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:351
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_is_wake
```
**Symbols:**

```
ffffffff818c90b0-ffffffff818c91e6: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff8208e824-ffffffff8208e838: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *ignore_list, const char *controller_in, unsigned int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:353
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_is_wake
```
**Symbols:**

```
ffffffff8190c170-ffffffff8190c2a6: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff8210eb23-ffffffff8210eb37: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool acpi_gpio_in_ignore_list(const char *ignore_list, const char *controller_in, unsigned int pin_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:329
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_is_wake
```
**Symbols:**

```
ffffffff81953d60-ffffffff81953e96: acpi_gpio_in_ignore_list (STB_LOCAL)
ffffffff821ec765-ffffffff821ec779: acpi_gpio_in_ignore_list.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca360)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567e1d)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81558c6d)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8156698d)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815808ad)
Location: drivers/gpio/gpiolib-acpi.c:208
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pin_in</code> ➡️ <code>unsigned int pin_in</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *ignore_list</code>
</li>
<li>
<b>Param reordered. </b>
<code>controller_in, pin_in</code> ➡️ <code>ignore_list, controller_in, pin_in</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
