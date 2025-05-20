# Function: <code>__assign_bit</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dbf9d)
Location: include/linux/bitops.h:246
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150a2d5)
Location: include/linux/bitops.h:246
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151eb01)
Location: include/linux/bitops.h:227
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154cc9d)
Location: include/linux/bitops.h:227
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81695665)
Location: include/linux/bitops.h:227
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156de8d)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b81f5)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816127d8)
Location: include/linux/bitops.h:249
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c2d5)
Location: include/linux/bitops.h:249
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81637860)
Location: include/linux/bitops.h:247
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786df5)
Location: include/linux/bitops.h:247
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161b192)
Location: include/linux/bitops.h:247
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a755)
Location: include/linux/bitops.h:247
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168a6a0)
Location: include/linux/bitops.h:248
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817efa2b)
Location: include/linux/bitops.h:248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a789f)
Location: include/linux/bitops.h:214
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aaeab)
Location: include/linux/bitops.h:214
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f7be)
Location: include/linux/bitops.h:214
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bfe5f)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c3c7d)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8db7e)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81902e3f)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81906d80)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad932e)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194aa0f)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194e5b8)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c61e)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In net/netlink/af_netlink.c (ffffffff81f85ae2)
Location: include/linux/bitops.h:284
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c384c)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7a90)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0861c94)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a46c4)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083ff28)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e618)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a8456)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e3a2)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156364d)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dc55)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155449d)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cd45)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815621bd)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac035)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157c0ad)
Location: include/linux/bitops.h:234
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c6495)
Location: include/linux/bitops.h:234
Inline: True
```
</details>
</li>
</ul>

## Differences
