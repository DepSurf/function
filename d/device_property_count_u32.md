# Function: <code>device_property_count_u32</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff8180807b)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
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
In drivers/usb/dwc2/params.c (ffffffff818d8bdd)
Location: include/linux/property.h:163
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81931dd7)
Location: include/linux/property.h:163
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_parse_fwnode_data
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
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
In drivers/usb/dwc2/params.c (ffffffff818e30dd)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81939037)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_parse_fwnode_data
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
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
In drivers/usb/dwc2/params.c (ffffffff818c6456)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191d709)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/mmc/core/host.c (ffffffff81991163)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
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
In drivers/usb/dwc2/params.c (ffffffff8195e583)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c02f1)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/mmc/core/host.c (ffffffff81a3cbe0)
Location: include/linux/property.h:166
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
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
In drivers/usb/dwc2/params.c (ffffffff81ab88d7)
Location: include/linux/property.h:172
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b21040)
Location: include/linux/property.h:172
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/mmc/core/host.c (ffffffff81ba9c7d)
Location: include/linux/property.h:172
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
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
In drivers/gpio/gpiolib.c (ffffffff818c1d85)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
```
```
In drivers/usb/dwc2/params.c (ffffffff81c41b47)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb32e0)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/mmc/core/host.c (ffffffff81d4ca8d)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
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
In drivers/gpio/gpiolib.c (ffffffff81904ce3)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
```
```
In drivers/usb/dwc2/params.c (ffffffff81ca910e)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1a90d)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/mmc/core/host.c (ffffffff81db73fd)
Location: include/linux/property.h:197
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
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
In drivers/gpio/gpiolib.c (ffffffff8194c602)
Location: include/linux/property.h:237
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges
```
```
In drivers/usb/dwc2/params.c (ffffffff81d5dd92)
Location: include/linux/property.h:237
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dd073a)
Location: include/linux/property.h:237
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_get_keymap_from_fwnode
```
```
In drivers/mmc/core/host.c (ffffffff81e6f8cd)
Location: include/linux/property.h:237
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffff800010a3feac)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (c0b12a18)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (c000000000b006e8)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffe00065bc5e)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
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
In drivers/usb/dwc2/params.c (ffffffff817c045b)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff817fcefb)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff8181700b)
Location: include/linux/property.h:158
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
</details>
</li>
</ul>

## Differences
