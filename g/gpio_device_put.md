# Function: <code>gpio_device_put</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8190028e)
Location: drivers/gpio/gpiolib.h:90
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81905f06)
Location: drivers/gpio/gpiolib.h:90
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gpio_device_put(struct gpio_device *gdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947c04)
Location: drivers/gpio/gpiolib.c:1197
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_release
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff81945fb0-ffffffff81945fc6: gpio_device_put (STB_GLOBAL)
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
</ul>
