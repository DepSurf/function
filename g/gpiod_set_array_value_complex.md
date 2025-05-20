# Function: <code>gpiod_set_array_value_complex</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81472070)
Location: drivers/gpio/gpiolib.c:2398
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81472070-ffffffff8147238f: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81494190)
Location: drivers/gpio/gpiolib.c:2588
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81494190-ffffffff814944af: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149d6e0)
Location: drivers/gpio/gpiolib.c:2585
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8149d6e0-ffffffff8149d9ea: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dc0f0)
Location: drivers/gpio/gpiolib.c:2838
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff814dc0f0-ffffffff814dc438: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150a440)
Location: drivers/gpio/gpiolib.c:3014
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8150a440-ffffffff8150a832: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151ee20)
Location: drivers/gpio/gpiolib.c:3141
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8151ee20-ffffffff8151f2ba: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3229
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8154f19f-ffffffff8154f1c5: gpiod_set_array_value_complex.cold (STB_LOCAL)
ffffffff8154cfc0-ffffffff8154d455: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156e1c0)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8156e1c0-ffffffff8156e660: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81612660)
Location: drivers/gpio/gpiolib.c:3992
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81612660-ffffffff81612b13: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81637700)
Location: drivers/gpio/gpiolib.c:2817
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
**Symbols:**

```
ffffffff81637700-ffffffff81637ba4: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161b030)
Location: drivers/gpio/gpiolib.c:2794
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
```
**Symbols:**

```
ffffffff8161b030-ffffffff8161b556: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2834
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
**Symbols:**

```
ffffffff81ce2034-ffffffff81ce2086: gpiod_set_array_value_complex.cold (STB_LOCAL)
ffffffff8168a530-ffffffff8168aa65: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81ea8a3a-ffffffff81ea8a98: gpiod_set_array_value_complex.cold (STB_LOCAL)
ffffffff817a7720-ffffffff817a7cdc: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3025
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
**Symbols:**

```
ffffffff8208e645-ffffffff8208e6a3: gpiod_set_array_value_complex.cold (STB_LOCAL)
ffffffff818bfce0-ffffffff818c02e1: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3066
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
**Symbols:**

```
ffffffff8210e947-ffffffff8210e9a6: gpiod_set_array_value_complex.cold (STB_LOCAL)
ffffffff81902cc0-ffffffff819032bf: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3259
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff821ec5a7-ffffffff821ec5f8: gpiod_set_array_value_complex.cold (STB_LOCAL)
ffffffff8194a890-ffffffff8194ae4a: gpiod_set_array_value_complex (STB_GLOBAL)
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c3c80)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffff8000106c3c80-ffff8000106c40e0: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0862060)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
c0862060-c0862544: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0000000008403a0)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
c0000000008403a0-c000000000840908: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a879c)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffe0004a879c-ffffffe0004a8b24: gpiod_set_array_value_complex (STB_GLOBAL)
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81563980)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81563980-ffffffff81563e20: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815547d0)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff815547d0-ffffffff81554c70: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815624f0)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff815624f0-ffffffff81562990: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157c3f0)
Location: drivers/gpio/gpiolib.c:3583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_array_value
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8157c3f0-ffffffff8157c8a9: gpiod_set_array_value_complex (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_array *array_info</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *value_bitmap</code>
</li>
<li>
<b>Param removed. </b>
<code>int *value_array</code>
</li>
</ul>
</details>
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
