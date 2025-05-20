# Function: <code>gpiochip_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81423fd0)
Location: drivers/gpio/gpiolib.c:445
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81423fd0-ffffffff81424046: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146d640)
Location: drivers/gpio/gpiolib.c:1361
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff8146d640-ffffffff8146d6cd: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148f510)
Location: drivers/gpio/gpiolib.c:1442
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff8148f510-ffffffff8148f59d: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81498f60)
Location: drivers/gpio/gpiolib.c:1433
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81498f60-ffffffff81498fef: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d7250)
Location: drivers/gpio/gpiolib.c:1464
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff814d7250-ffffffff814d72e1: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506410)
Location: drivers/gpio/gpiolib.c:1572
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff81506410-ffffffff8150649f: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151a8c0)
Location: drivers/gpio/gpiolib.c:1572
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff8151a8c0-ffffffff8151a94f: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81548a60)
Location: drivers/gpio/gpiolib.c:1591
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff81548a60-ffffffff81548af0: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81569ab0)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff81569ab0-ffffffff81569b40: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160ed0a)
Location: drivers/gpio/gpiolib.c:1929
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff8160c3e0-ffffffff8160c470: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8163615a)
Location: drivers/gpio/gpiolib.c:876
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff81633220-ffffffff816332b0: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161b9b2)
Location: drivers/gpio/gpiolib.c:865
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff81616f00-ffffffff81616f90: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168aec2)
Location: drivers/gpio/gpiolib.c:887
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
```
**Symbols:**

```
ffffffff81686180-ffffffff81686210: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a8205)
Location: drivers/gpio/gpiolib.c:917
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
```
**Symbols:**

```
ffffffff817a2b00-ffffffff817a2b98: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c0a35)
Location: drivers/gpio/gpiolib.c:990
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff818b9d60-ffffffff818b9df8: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81903a7d)
Location: drivers/gpio/gpiolib.c:1021
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff818fce50-ffffffff818fcee8: gpiochip_find (STB_GLOBAL)
```
</details>
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
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c0038)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
ffff8000106c0038-ffff8000106c0140: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085cd7c)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
c085cd7c-c085ce10: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000838f80)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
c000000000838f80-c0000000008390c0: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a3fde)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
ffffffe0004a3fde-ffffffe0004a406a: gpiochip_find (STB_GLOBAL)
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
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f270)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff8155f270-ffffffff8155f300: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815500c0)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff815500c0-ffffffff81550150: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155dde0)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff8155dde0-ffffffff8155de70: gpiochip_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gpio_chip *gpiochip_find(void *data, int (*match)(struct gpio_chip *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81577c70)
Location: drivers/gpio/gpiolib.c:1600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
```
**Symbols:**

```
ffffffff81577c70-ffffffff81577d00: gpiochip_find (STB_GLOBAL)
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
