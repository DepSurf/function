# Function: <code>gpiod_get_array_value_complex</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dbd00)
Location: drivers/gpio/gpiolib.c:2613
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff814dbd00-ffffffff814dc02d: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509f90)
Location: drivers/gpio/gpiolib.c:2771
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81509f90-ffffffff8150a371: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151e880)
Location: drivers/gpio/gpiolib.c:2851
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8151e880-ffffffff8151ed52: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2939
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8154f166-ffffffff8154f19f: gpiod_get_array_value_complex.cold (STB_LOCAL)
ffffffff8154ca40-ffffffff8154cef4: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156dc30)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8156dc30-ffffffff8156e0f2: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816120c0)
Location: drivers/gpio/gpiolib.c:3705
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff816120c0-ffffffff8161259c: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81637150)
Location: drivers/gpio/gpiolib.c:2531
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
```
**Symbols:**

```
ffffffff81637150-ffffffff8163763e: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161aa60)
Location: drivers/gpio/gpiolib.c:2508
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
```
**Symbols:**

```
ffffffff8161aa60-ffffffff8161af6f: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2537
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
```
**Symbols:**

```
ffffffff81ce1fd0-ffffffff81ce2034: gpiod_get_array_value_complex.cold (STB_LOCAL)
ffffffff81689ea0-ffffffff8168a46e: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2658
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81ea89c9-ffffffff81ea8a3a: gpiod_get_array_value_complex.cold (STB_LOCAL)
ffffffff817a6f70-ffffffff817a75a8: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2728
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
**Symbols:**

```
ffffffff8208e5ee-ffffffff8208e645: gpiod_get_array_value_complex.cold (STB_LOCAL)
ffffffff818bf460-ffffffff818bfb16: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2769
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
**Symbols:**

```
ffffffff8210e8f0-ffffffff8210e947: gpiod_get_array_value_complex.cold (STB_LOCAL)
ffffffff819024d0-ffffffff81902af1: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2962
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff821ec543-ffffffff821ec5a7: gpiod_get_array_value_complex.cold (STB_LOCAL)
ffffffff8194a0c0-ffffffff8194a6b4: gpiod_get_array_value_complex (STB_GLOBAL)
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c3638)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffff8000106c3638-ffff8000106c3b00: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0861a30)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
c0861a30-c0861f38: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083fcf0)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
c00000000083fcf0-c000000000840294: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a82b4)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffe0004a82b4-ffffffe0004a866c: gpiod_get_array_value_complex (STB_GLOBAL)
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815633f0)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff815633f0-ffffffff815638b2: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81554240)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81554240-ffffffff81554702: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561f60)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81561f60-ffffffff81562422: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157be50)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8157be50-ffffffff8157c32b: gpiod_get_array_value_complex (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
