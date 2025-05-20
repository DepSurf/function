# Function: <code>gpiod_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426d80)
Location: drivers/gpio/gpiolib.c:1002
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
```
**Symbols:**

```
ffffffff81426d80-ffffffff81426daf: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81471150)
Location: drivers/gpio/gpiolib.c:1954
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81471150-ffffffff81471194: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814932c0)
Location: drivers/gpio/gpiolib.c:2141
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff814932c0-ffffffff81493304: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149cbd0)
Location: drivers/gpio/gpiolib.c:2142
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8149cbd0-ffffffff8149cc11: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814db1d0)
Location: drivers/gpio/gpiolib.c:2279
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff814db1d0-ffffffff814db211: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509420)
Location: drivers/gpio/gpiolib.c:2393
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81509420-ffffffff81509463: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151ddb0)
Location: drivers/gpio/gpiolib.c:2422
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8151ddb0-ffffffff8151ddf3: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154bee0)
Location: drivers/gpio/gpiolib.c:2486
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8154bee0-ffffffff8154bf23: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156d050)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8156d050-ffffffff8156d093: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f5e6)
Location: drivers/gpio/gpiolib.c:3194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib.c:linehandle_release
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81612070-ffffffff816120b9: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636046)
Location: drivers/gpio/gpiolib.c:2003
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff816370a0-ffffffff816370e9: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816197a6)
Location: drivers/gpio/gpiolib.c:1980
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8161a9c0-ffffffff8161aa09: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81688bc6)
Location: drivers/gpio/gpiolib.c:2002
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81689e00-ffffffff81689e49: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5396)
Location: drivers/gpio/gpiolib.c:2063
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_release
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff817a6e80-ffffffff817a6ee1: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd5f6)
Location: drivers/gpio/gpiolib.c:2133
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_release
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff818bf360-ffffffff818bf3bd: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900276)
Location: drivers/gpio/gpiolib.c:2168
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_release
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff819023e0-ffffffff81902425: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947be6)
Location: drivers/gpio/gpiolib.c:2347
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_release
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81949f20-ffffffff81949f6b: gpiod_free (STB_GLOBAL)
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
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2788)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffff8000106c2788-ffff8000106c27ec: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860da0)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c0860da0-c0860df0: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083ed10)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c00000000083ed10-c00000000083eda4: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a78c0)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffe0004a78c0-ffffffe0004a7916: gpiod_free (STB_GLOBAL)
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
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562810)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81562810-ffffffff81562853: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81553660)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81553660-ffffffff815536a3: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561380)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81561380-ffffffff815613c3: gpiod_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void gpiod_free(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157b270)
Location: drivers/gpio/gpiolib.c:2818
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8157b270-ffffffff8157b2b3: gpiod_free (STB_GLOBAL)
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
