# Function: <code>gpiochip_get_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814246ba)
Location: drivers/gpio/gpiolib.c:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81426bd0-ffffffff81426bfc: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81471d31)
Location: drivers/gpio/gpiolib.c:112
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff81470f20-ffffffff81470f50: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81493f19)
Location: drivers/gpio/gpiolib.c:115
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81493090-ffffffff814930c0: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149dd8d)
Location: drivers/gpio/gpiolib.c:116
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8149ca40-ffffffff8149ca70: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dc94e)
Location: drivers/gpio/gpiolib.c:131
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff814db040-ffffffff814db070: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150ad05)
Location: drivers/gpio/gpiolib.c:139
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81509310-ffffffff81509340: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f875)
Location: drivers/gpio/gpiolib.c:140
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8151dca0-ffffffff8151dcd0: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154da15)
Location: drivers/gpio/gpiolib.c:140
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8154bdc0-ffffffff8154bdf3: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156ec15)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8156cf30-ffffffff8156cf63: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160edd5)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8160c2c0-ffffffff8160c2ee: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636218)
Location: drivers/gpio/gpiolib.c:139
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
**Symbols:**

```
ffffffff81633160-ffffffff81633192: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161bac6)
Location: drivers/gpio/gpiolib.c:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81616e40-ffffffff81616e72: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168afd6)
Location: drivers/gpio/gpiolib.c:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
```
**Symbols:**

```
ffffffff816860c0-ffffffff816860f2: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a4ca4)
Location: drivers/gpio/gpiolib.c:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib.c:gpio_name_to_desc
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
```
**Symbols:**

```
ffffffff817a29a0-ffffffff817a29de: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bbd5b)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib.c:gpio_name_to_desc
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff818b9c60-ffffffff818b9c9e: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ff24b)
Location: drivers/gpio/gpiolib.c:159
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib.c:gpio_name_to_desc
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff818fcd50-ffffffff818fcd8e: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *gc, unsigned int hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194660e)
Location: drivers/gpio/gpiolib.c:138
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_dup_line_label
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
  - drivers/gpio/gpiolib.c:gpio_name_to_desc
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff819442e0-ffffffff81944339: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c49ec)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffff8000106c2620-ffff8000106c2674: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0862d44)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
```
**Symbols:**

```
c0860c84-c0860cb8: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841524)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
```
**Symbols:**

```
c00000000083eb80-c00000000083ebb8: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a91a8)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_machine_hog
```
**Symbols:**

```
ffffffe0004a779c-ffffffe0004a77d8: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815643d5)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff815626f0-ffffffff81562723: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81555225)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81553540-ffffffff81553573: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562f45)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81561260-ffffffff81561293: gpiochip_get_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiochip_get_desc(struct gpio_chip *chip, u16 hwnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157ce65)
Location: drivers/gpio/gpiolib.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8157b150-ffffffff8157b183: gpiochip_get_desc (STB_GLOBAL)
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
