# Function: <code>gpiod_set_raw_array_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814268a0)
Location: drivers/gpio/gpiolib.c:1545
Inline: False
```
**Symbols:**

```
ffffffff814268a0-ffffffff814268c5: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81472520)
Location: drivers/gpio/gpiolib.c:2502
Inline: False
```
**Symbols:**

```
ffffffff81472520-ffffffff81472545: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81494640)
Location: drivers/gpio/gpiolib.c:2692
Inline: False
```
**Symbols:**

```
ffffffff81494640-ffffffff81494665: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149db70)
Location: drivers/gpio/gpiolib.c:2689
Inline: True
```
**Symbols:**

```
ffffffff8149db70-ffffffff8149db96: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dc5d0)
Location: drivers/gpio/gpiolib.c:2960
Inline: True
```
**Symbols:**

```
ffffffff814dc5d0-ffffffff814dc5f6: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, int *value_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150a9d0)
Location: drivers/gpio/gpiolib.c:3152
Inline: False
```
**Symbols:**

```
ffffffff8150a9d0-ffffffff8150a9fa: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151f470)
Location: drivers/gpio/gpiolib.c:3318
Inline: False
```
**Symbols:**

```
ffffffff8151f470-ffffffff8151f49d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154d600)
Location: drivers/gpio/gpiolib.c:3407
Inline: False
```
**Symbols:**

```
ffffffff8154d600-ffffffff8154d62d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156e800)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffffffff8156e800-ffffffff8156e82d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81612cf0)
Location: drivers/gpio/gpiolib.c:4167
Inline: False
```
**Symbols:**

```
ffffffff81612cf0-ffffffff81612d1d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81637bb0)
Location: drivers/gpio/gpiolib.c:2991
Inline: False
```
**Symbols:**

```
ffffffff81637bb0-ffffffff81637bdd: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161b560)
Location: drivers/gpio/gpiolib.c:2968
Inline: False
```
**Symbols:**

```
ffffffff8161b560-ffffffff8161b58d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168aa70)
Location: drivers/gpio/gpiolib.c:3017
Inline: False
```
**Symbols:**

```
ffffffff8168aa70-ffffffff8168aa9d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a7ce0)
Location: drivers/gpio/gpiolib.c:3138
Inline: False
```
**Symbols:**

```
ffffffff817a7ce0-ffffffff817a7d31: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c0300)
Location: drivers/gpio/gpiolib.c:3208
Inline: False
```
**Symbols:**

```
ffffffff818c0300-ffffffff818c0351: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819032d0)
Location: drivers/gpio/gpiolib.c:3249
Inline: False
```
**Symbols:**

```
ffffffff819032d0-ffffffff81903321: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194ae60)
Location: drivers/gpio/gpiolib.c:3442
Inline: False
```
**Symbols:**

```
ffffffff8194ae60-ffffffff8194aeb1: gpiod_set_raw_array_value (STB_GLOBAL)
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
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c43e8)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffff8000106c43e8-ffff8000106c4448: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0862774)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
c0862774-c08627c0: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000840ba0)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
c000000000840ba0-c000000000840bdc: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a8c6a)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffffffe0004a8c6a-ffffffe0004a8cb6: gpiod_set_raw_array_value (STB_GLOBAL)
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
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81563fc0)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffffffff81563fc0-ffffffff81563fed: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81554e10)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffffffff81554e10-ffffffff81554e3d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562b30)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffffffff81562b30-ffffffff81562b5d: gpiod_set_raw_array_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_set_raw_array_value(unsigned int array_size, struct gpio_desc **desc_array, struct gpio_array *array_info, long unsigned int *value_bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157ca50)
Location: drivers/gpio/gpiolib.c:3761
Inline: False
```
**Symbols:**

```
ffffffff8157ca50-ffffffff8157ca7d: gpiod_set_raw_array_value (STB_GLOBAL)
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
