# Function: <code>gpiolib_cdev_register</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163c1b0)
Location: drivers/gpio/gpiolib-cdev.c:2356
Inline: False
```
**Symbols:**

```
ffffffff8163c1b0-ffffffff8163c250: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161fcf0)
Location: drivers/gpio/gpiolib-cdev.c:2357
Inline: False
```
**Symbols:**

```
ffffffff8161fcf0-ffffffff8161fd90: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168f280)
Location: drivers/gpio/gpiolib-cdev.c:2357
Inline: False
```
**Symbols:**

```
ffffffff8168f280-ffffffff8168f31d: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ae570)
Location: drivers/gpio/gpiolib-cdev.c:2552
Inline: False
```
**Symbols:**

```
ffffffff817ae570-ffffffff817ae631: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c7a00)
Location: drivers/gpio/gpiolib-cdev.c:2738
Inline: False
```
**Symbols:**

```
ffffffff818c7a00-ffffffff818c7ac4: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190aaa0)
Location: drivers/gpio/gpiolib-cdev.c:2735
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
```
**Symbols:**

```
ffffffff8190aaa0-ffffffff8190ab64: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiolib_cdev_register(struct gpio_device *gdev, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81952790)
Location: drivers/gpio/gpiolib-cdev.c:2785
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
```
**Symbols:**

```
ffffffff81952790-ffffffff81952854: gpiolib_cdev_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
