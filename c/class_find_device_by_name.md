# Function: <code>class_find_device_by_name</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81866295)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffff818e4ca0)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/video/backlight/backlight.c (ffffffff81664cf5)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff818865a5)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff81939c15)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffff819b7ce2)
Location: include/linux/device/class.h:127
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
In drivers/video/backlight/backlight.c (ffffffff81685989)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81894a39)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff81940079)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffff819ba162)
Location: include/linux/device/class.h:127
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
In drivers/video/backlight/backlight.c (ffffffff81668789)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877339)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff819237e9)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffff8199ea14)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/video/backlight/backlight.c (ffffffff816dba69)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81908079)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff819c6799)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/ptp/ptp_vclock.c (ffffffff819db0ff)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
```
```
In drivers/leds/led-class.c (ffffffff81a4b6b7)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/video/backlight/backlight.c (ffffffff81805709)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5b1f9)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff81b27509)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3eb47)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
```
```
In drivers/leds/led-class.c (ffffffff81bb9ca2)
Location: include/linux/device/class.h:127
Inline: True
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
In drivers/video/backlight/backlight.c (ffffffff81934039)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be5b89)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff81cbaea9)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4ec7)
Location: include/linux/device/class.h:127
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
```
```
In drivers/leds/led-class.c (ffffffff81d5f0c2)
Location: include/linux/device/class.h:127
Inline: True
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
In drivers/video/backlight/backlight.c (ffffffff819784f9)
Location: include/linux/device/class.h:108
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3d5a9)
Location: include/linux/device/class.h:108
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff81d22659)
Location: include/linux/device/class.h:108
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cb27)
Location: include/linux/device/class.h:108
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
```
```
In drivers/leds/led-class.c (ffffffff81dca518)
Location: include/linux/device/class.h:108
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_get
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
In drivers/video/backlight/backlight.c (ffffffff819c25e9)
Location: include/linux/device/class.h:106
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_get_by_name
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf2959)
Location: include/linux/device/class.h:106
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_find_bus
```
```
In drivers/rtc/interface.c (ffffffff81dd83b9)
Location: include/linux/device/class.h:106
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df3467)
Location: include/linux/device/class.h:106
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
```
```
In drivers/leds/led-class.c (ffffffff81e83088)
Location: include/linux/device/class.h:106
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_get
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
In drivers/usb/roles/class.c (ffff800010a914c0)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_match
```
```
In drivers/rtc/interface.c (ffff800010aa76b8)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffff800010b49aac)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/usb/roles/class.c (c0b74d38)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_match
```
```
In drivers/rtc/interface.c (c0b868c8)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (c0c32ef8)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/rtc/interface.c (c000000000b89400)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (c000000000c3e184)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/rtc/interface.c (ffffffe0006b3808)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffe00071d03c)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81818f45)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e0635)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
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
In drivers/rtc/interface.c (ffffffff8185a425)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffff818d9b00)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In drivers/rtc/interface.c (ffffffff81875505)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_class_open
```
```
In drivers/leds/led-class.c (ffffffff818f6620)
Location: include/linux/device.h:646
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
</details>
</li>
</ul>

## Differences
