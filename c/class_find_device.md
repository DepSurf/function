# Function: <code>class_find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154d1c0)
Location: drivers/base/class.c:412
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff8154d1c0-ffffffff8154d2ab: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159efb0)
Location: drivers/base/class.c:412
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff8159efb0-ffffffff8159f09b: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd570)
Location: drivers/base/class.c:427
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff815cd570-ffffffff815cd65b: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e2070)
Location: drivers/base/class.c:394
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff815e2070-ffffffff815e2162: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816491e0)
Location: drivers/base/class.c:394
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816491e0-ffffffff816492d4: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816847a0)
Location: drivers/base/class.c:392
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816847a0-ffffffff81684883: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a4460)
Location: drivers/base/class.c:392
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport_children
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816a4460-ffffffff816a453f: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dd370)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816dd370-ffffffff816dd453: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81701420)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81701420-ffffffff81701503: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bb3e0)
Location: drivers/base/class.c:399
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
**Symbols:**

```
ffffffff817bb3e0-ffffffff817bb4db: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817cffd0)
Location: drivers/base/class.c:399
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
**Symbols:**

```
ffffffff817cffd0-ffffffff817d00cb: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b39e0)
Location: drivers/base/class.c:399
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817b39e0-ffffffff817b3ae0: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183cec0)
Location: drivers/base/class.c:399
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff8183cec0-ffffffff8183cfc0: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197fa70)
Location: drivers/base/class.c:399
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_put_debugfs_dir
  - drivers/net/wwan/wwan_core.c:wwan_get_debugfs_dir
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
**Symbols:**

```
ffffffff8197fa70-ffffffff8197fb8f: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aed380)
Location: drivers/base/class.c:404
Inline: False
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_put_debugfs_dir
  - drivers/net/wwan/wwan_core.c:wwan_get_debugfs_dir
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
**Symbols:**

```
ffffffff81aed380-ffffffff81aed49f: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *class_find_device(const struct class *class, const struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b7b0)
Location: drivers/base/class.c:436
Inline: False
Direct callers:
  - block/early-lookup.c:devt_from_partuuid
  - block/early-lookup.c:early_lookup_bdev
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_newlink
  - drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_put_debugfs_dir
  - drivers/net/wwan/wwan_core.c:wwan_get_debugfs_dir
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_get
```
**Symbols:**

```
ffffffff81b3b7b0-ffffffff81b3b93c: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *class_find_device(const struct class *class, const struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b93300)
Location: drivers/base/class.c:435
Inline: False
Direct callers:
  - block/early-lookup.c:devt_from_partuuid
  - block/early-lookup.c:early_lookup_bdev
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
  - drivers/usb/roles/class.c:usb_role_switch_find_by_fwnode
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_get
```
**Symbols:**

```
ffffffff81b93300-ffffffff81b9348c: class_find_device (STB_GLOBAL)
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
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108eccb8)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:of_find_backlight
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/net-sysfs.c:of_find_net_device_by_node
```
**Symbols:**

```
ffff8000108eccb8-ffff8000108ecdb0: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09dab34)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:of_find_backlight
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/net-sysfs.c:of_find_net_device_by_node
```
**Symbols:**

```
c09dab34-c09dac3c: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c0000000009847f0)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/video/backlight/backlight.c:of_find_backlight
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/net-sysfs.c:of_find_net_device_by_node
```
**Symbols:**

```
c0000000009847f0-c00000000098494c: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fed8)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/of_regulator.c:of_parse_coupled_regulator
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/net/phy/mdio_bus.c:of_mdio_find_bus
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/net-sysfs.c:of_find_net_device_by_node
```
**Symbols:**

```
ffffffe00057fed8-ffffffe00057ff90: class_find_device (STB_GLOBAL)
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
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c6c10)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
**Symbols:**

```
ffffffff816c6c10-ffffffff816c6cf3: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a1e70)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
**Symbols:**

```
ffffffff816a1e70-ffffffff816a1f53: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f50e0)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816f50e0-ffffffff816f51c3: class_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *class_find_device(struct class *class, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f970)
Location: drivers/base/class.c:398
Inline: True
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/base/core.c:device_destroy
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/spi/spi.c:spi_busnum_to_master
  - drivers/rtc/interface.c:rtc_class_open
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff8170f970-ffffffff8170fa53: class_find_device (STB_GLOBAL)
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
<li>
<b>Param type changed. </b>
<code>struct device *start</code> ➡️ <code>const struct device *start</code>
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
