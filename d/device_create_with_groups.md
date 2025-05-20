# Function: <code>device_create_with_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548d00)
Location: drivers/base/core.c:1818
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff81548d00-ffffffff81548d5d: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a930)
Location: drivers/base/core.c:1818
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff8159a930-ffffffff8159a98d: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8e90)
Location: drivers/base/core.c:2409
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff815c8e90-ffffffff815c8eed: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815ddba0)
Location: drivers/base/core.c:2407
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff815ddba0-ffffffff815ddbf5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644ba0)
Location: drivers/base/core.c:2542
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff81644ba0-ffffffff81644bf5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167ffc0)
Location: drivers/base/core.c:2589
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8167ffc0-ffffffff81680015: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ed00)
Location: drivers/base/core.c:2664
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8169ed00-ffffffff8169ed55: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d72b0)
Location: drivers/base/core.c:2918
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816d72b0-ffffffff816d7305: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb3b0)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816fb3b0-ffffffff816fb405: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b45d0)
Location: drivers/base/core.c:3423
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817b45d0-ffffffff817b4625: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817cabf0)
Location: drivers/base/core.c:3835
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817cabf0-ffffffff817cac45: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ae560)
Location: drivers/base/core.c:4062
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817ae560-ffffffff817ae5b5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81837780)
Location: drivers/base/core.c:4127
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81837780-ffffffff818377d5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81979880)
Location: drivers/base/core.c:4161
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81979880-ffffffff819798f5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae6390)
Location: drivers/base/core.c:4380
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81ae6390-ffffffff81ae6405: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *device_create_with_groups(const struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b34730)
Location: drivers/base/core.c:4383
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b34730-ffffffff81b347a5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *device_create_with_groups(const struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8c160)
Location: drivers/base/core.c:4396
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b8c160-ffffffff81b8c1d5: device_create_with_groups (STB_GLOBAL)
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
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e5ac0)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffff8000108e5ac0-ffff8000108e5b80: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4158)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
c09d4158-c09d41c4: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097b520)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
c00000000097b520-c00000000097b55c: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a6d6)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffe00057a6d6-ffffffe00057a736: device_create_with_groups (STB_GLOBAL)
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
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0ba0)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
```
**Symbols:**

```
ffffffff816c0ba0-ffffffff816c0bf5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169be50)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
```
**Symbols:**

```
ffffffff8169be50-ffffffff8169bea5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef070)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816ef070-ffffffff816ef0c5: device_create_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *device_create_with_groups(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817096d0)
Location: drivers/base/core.c:2955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_register
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817096d0-ffffffff81709725: device_create_with_groups (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *class</code> ➡️ <code>const struct class *class</code>
</li>
</ul>
</details>
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
